<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hipy_jshs"/><path class="k2_qufb6m"/><path class="xd2zlwg4n"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dgnx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hipy_jshs {
  fill: var(--svg-color--0f978e, #0f978e);
  d: path("M24 0H0v24h24z");
}

.k2_qufb6m {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.345 6.514c-.282-.282-.579-.127-.819.108L9.424 8.726c-.283.283-.56.137-.81-.113L8.04 8.04c-.282-.282-.165-.541.09-.795l2.612-2.608c.249-.254.442-.409.578-.48a1.45 1.45 0 0 1 1.38.038q.167.098.484.414l6.377 6.363a1.425 1.425 0 0 1 .333 1.569c-.073.176-.18.335-.314.469l-6.542 6.55a1.46 1.46 0 0 1-1.722.274a2.4 2.4 0 0 1-.471-.39l-2.828-2.815a.43.43 0 0 1-.127-.433c.075-.259.536-.64.738-.847c.32-.316.551-.339.871-.024l2.127 2.123c.306.301.565.174.833-.094l5.027-5.012c.268-.264.155-.542-.085-.782z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xd2zlwg4n {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.495 11.653c-.212.221-.127.494.061.696l.48.5c.349.357.405.573.048.936c-.217.211-.542.611-.777.706c-.179.075-.344.033-.504-.127l-1.266-1.271a2 2 0 0 1-.409-.527a1.43 1.43 0 0 1 .282-1.591q.694-.703 1.389-1.393c.136-.136.282-.179.447-.141c.25.07.579.461.781.659c.362.353.424.565.066.94zm5.403.113l-1.064-1.06a.354.354 0 0 0-.498 0l-1.055 1.06a.347.347 0 0 0 0 .498l1.064 1.06a.347.347 0 0 0 .499 0l1.054-1.064a.347.347 0 0 0 0-.5z");
}

</style>
