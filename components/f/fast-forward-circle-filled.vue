<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGwtRh7dps"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="v1z3zramy"/><path clip-rule="evenodd" class="zj1n8v_yy"/><path class="hmfowj91c"/><path clip-rule="evenodd" class="y78w3tb0t"/></g></mask></defs><circle mask="url(#SVGwtRh7dps)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:fast-forward-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.hmfowj91c {
  d: path("M19.363 12.318a1 1 0 0 1 0 1.364l-4.632 4.963c-.62.664-1.731.226-1.731-.682V8.037c0-.908 1.112-1.346 1.731-.682z");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.v1z3zramy {
  d: path("M14.363 12.318a1 1 0 0 1 0 1.364l-4.632 4.963c-.62.664-1.731.226-1.731-.682V8.037c0-.908 1.112-1.346 1.731-.682z");
}

.y78w3tb0t {
  fill-rule: evenodd;
  d: path("M17.264 13L15 10.574v4.852zm2.1.682a1 1 0 0 0 0-1.364L14.73 7.355c-.619-.665-1.73-.226-1.73.682v9.926c0 .908 1.112 1.346 1.731.682z");
}

.zj1n8v_yy {
  fill-rule: evenodd;
  d: path("M12.264 13L10 10.574v4.852zm2.1.682a1 1 0 0 0 0-1.364L9.73 7.355C9.111 6.69 8 7.129 8 8.037v9.926c0 .908 1.112 1.346 1.731.682z");
}

</style>
