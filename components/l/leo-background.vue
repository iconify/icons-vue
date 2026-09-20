<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGzu0nzdbg)" class="r4i437pya"/><path class="jfwr8cpks"/></g><defs><linearGradient id="SVGzu0nzdbg" x1="12" x2="12" y1="4" y2="20.005" gradientUnits="userSpaceOnUse"><stop class="r4_qxlbeh"/><stop offset=".13" class="nqwt5jb2r"/><stop offset=".35" class="ll9--ib7o"/><stop offset=".64" class="i84mf0b0d"/><stop offset=".98" class="i1fo_yb_q"/><stop offset="1" class="ax7x9d8wu"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:leo-background" /></template>
<style>
.ax7x9d8wu {
  stop-color: var(--svg-color--eb5c2c, #eb5c2c);
}

.ft5dv1b6b {
  fill: none;
}

.i1fo_yb_q {
  stop-color: var(--svg-color--eb5e2c, #eb5e2c);
}

.i84mf0b0d {
  stop-color: var(--svg-color--f59c2e, #f59c2e);
}

.jfwr8cpks {
  fill: var(--svg-color--fff, #fff);
  d: path("M16 10.828V6.372L11.877 4l-1.797.977l.73.429l1.044-.554l3.257 1.936v3.434h-1.778v1.698zm-10.222-.606V8.246L9.053 6.24l2.767 1.48l.011-.028l.343-.63l-3.12-1.77l-4.137 2.53l-.01 2.4zm2.425.635l2.464 1.057v-1.692H8.042l-3.126 1.492l-.028 4.132l1.785 1.257l.477-.653l-1.373-.987V12.12zm4.758 7.777l-1.118.457l-2.954-1.554v-3.371h-.89v3.828L11.804 20l1.438-.583zm4.372-3.005v-1.407h.889v1.795l-4.057 2.96l-2.61-2.097v-2.063l-2.353-2.373h5.225l-1.983 2.368v1.714l1.738 1.348zm.009-8.617l1.769 1.41v4.16l-3.412 2.126l-.399-.629l2.922-1.907V8.766L16.835 7.72l.507-.714z");
}

.ll9--ib7o {
  stop-color: var(--svg-color--f7c730, #f7c730);
}

.nqwt5jb2r {
  stop-color: var(--svg-color--f8e330, #f8e330);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4_qxlbeh {
  stop-color: var(--svg-color--f6e93d, #f6e93d);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
