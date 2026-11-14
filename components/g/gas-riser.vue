<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bl-bc0bbs"/><path class="dfi9sgben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gas-riser" /></template>
<style>
.bl-bc0bbs {
  d: path("M12.73 21.5h-.98q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088t-.138-.102t-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167q-.017-.084-.026-.169T10 19.75V8.797q0-.188.04-.371q.04-.184.118-.354q.078-.171.19-.321q.112-.151.254-.274l4-3.478q.059-.051.123-.097q.063-.046.13-.086q.068-.04.138-.074t.144-.061t.149-.049q.076-.02.153-.034t.155-.021t.156-.007t.156.007t.155.021t.153.034t.149.049q.073.027.144.061t.138.074t.13.086t.123.097l4 3.478q.142.123.254.274q.112.15.19.321q.078.17.118.354t.04.371v4.248");
}

.dfi9sgben {
  d: path("M3 21.5V13a2 2 0 0 1 2-2h5m0 3H6v7.5m11.5-8c2.25 1.5 4 3 4 4.5a3.5 3.5 0 0 1-7 0c0-1.25.75-2.25 1.5-3c.25 1 .75 1.5 1.5 1.75c-.5-1.25-.5-2.25 0-3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
