<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hxyghocib"/><path class="n8-91eb0z"/><path class="p5rts3bzh"/><path class="lzqp3jbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-ghana" /></template>
<style>
.hxyghocib {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M0 25h64v14H0z");
}

.lzqp3jbyp {
  fill: var(--svg-color--25333a, #25333a);
  d: path("m31.778 25.825l1.947 3.945l4.355.638l-3.149 3.072l.744 4.333l-3.897-2.047l-3.896 2.047l.744-4.333l-3.15-3.072l4.356-.638z");
}

.n8-91eb0z {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v4h64v-4c0-6.075-3.373-11-10-11");
}

.p5rts3bzh {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-4H0z");
}

</style>
