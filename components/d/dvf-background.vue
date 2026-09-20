<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGnK0d1pVv)" class="r4i437pya"/><path class="xp35f13pe"/><path clip-rule="evenodd" class="isyhkdbji"/></g><defs><linearGradient id="SVGnK0d1pVv" x1="4.771" x2="20.84" y1="18.667" y2="15.226" gradientUnits="userSpaceOnUse"><stop class="x3vl0hzwo"/><stop offset=".5" class="jr4dmxbnd"/><stop offset=".88" class="tvgoomo5u"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dvf-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.isyhkdbji {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-.47a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06");
}

.jr4dmxbnd {
  stop-color: var(--svg-color--ed5f5e, #ed5f5e);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tvgoomo5u {
  stop-color: var(--svg-color--67c9cb, #67c9cb);
}

.x3vl0hzwo {
  stop-color: var(--svg-color--fcdea0, #fcdea0);
}

.xp35f13pe {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.87 12.165c-.678-.085-.936-.273-.979-.353c-.061.748.207 2.24 1.755 2.24c1.544 0 1.986-1.252 2.015-1.883h.098c.142.245.127.56.1.683a2.11 2.11 0 0 1 1.515 1.972h.705c0-1.271-.47-2-.706-2.193l.071-.132c.376.201.675.522.847.913l.127.047c.979.438 1.713.127 1.963-.085a1.86 1.86 0 0 1-.26-.786h.194c.01.057.094.283.367.753c.24.419.682.504 1.115.588c.174.033.348.066.504.118c.433.155.451.584.409.777h.466v-.377c0-.423-.245-.786-.47-1.115c-.194-.283-.377-.541-.377-.8c0-.457.254-.796.376-.908c-.108-.033-.197-.16-.306-.316c-.16-.23-.362-.527-.767-.659a1.5 1.5 0 0 0-.611-.075c-.208.005-.5.014-1.069-.047c-.527-.061-.847-.33-1.19-.612c-.424-.362-.88-.738-1.789-.738c-1.303 0-1.74 1.096-1.802 1.646a1.1 1.1 0 0 0-.593-.465c.005.583-.132 1.298-.706 1.538c-.47.198-.86-.131-1.002-.32c-.184.198-.075.471 0 .589m3.53 2.659a2.34 2.34 0 0 0-.085-1.3l.09-.046c.507.386.583 1.073.554 1.346zm4.117-1.238c.09.122.377.395.8.508a1.6 1.6 0 0 1-.376.73h-.664c.17-.189.428-.716.132-1.125z");
}

</style>
