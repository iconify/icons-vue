<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a_f2fvb8a"/><path class="dib83cbyv"/><path class="k3evd1bhw"/><path class="jv0bpybqw"/><path class="feh4cdcvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dseth" /></template>
<style>
.a_f2fvb8a {
  fill: var(--svg-color--fdfeff, #fdfeff);
  d: path("m9.632 16.557l-5.21-3.135L9.632 21z");
}

.dib83cbyv {
  fill: var(--svg-color--b6c5c2, #b6c5c2);
  d: path("m14.368 16.557l5.21-3.135L14.368 21z");
}

.feh4cdcvy {
  fill: var(--svg-color--869193, #869193);
  d: path("M12 9.158v5.684l5.21-3.316z");
}

.ft5dv1b6b {
  fill: none;
}

.jv0bpybqw {
  fill: var(--svg-color--b6c5c2, #b6c5c2);
  d: path("M12.001 9.157v5.684l-5.21-3.315zm0 .237V3l5.21 8.526z");
}

.k3evd1bhw {
  fill: var(--svg-color--fdfeff, #fdfeff);
  d: path("M12.001 9.394V3l-5.21 8.526z");
}

</style>
