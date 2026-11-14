<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uk2zwactg"/><path class="b_jbgfyxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:component-override" /></template>
<style>
.b_jbgfyxk {
  d: path("m13.5 13.5l7 2.75l-3 1.25l-1.25 3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uk2zwactg {
  d: path("m11.797 16.703l-.236.236q-.052.052-.109.099t-.118.088t-.127.075q-.065.035-.133.063q-.068.029-.138.05t-.143.036q-.073.014-.146.021t-.147.008t-.147-.008q-.073-.007-.146-.021q-.072-.015-.143-.036t-.138-.05q-.068-.028-.133-.063q-.065-.034-.127-.075q-.061-.041-.118-.088t-.109-.099l-5.378-5.378q-.052-.052-.099-.109t-.088-.118t-.075-.127t-.063-.133t-.05-.138t-.036-.143t-.021-.146q-.008-.073-.008-.147t.008-.147t.021-.146q.015-.072.036-.143t.05-.138q.028-.068.063-.133q.034-.065.075-.127q.041-.061.088-.118t.099-.109l5.378-5.378q.052-.052.109-.099t.118-.088t.127-.075t.133-.063t.138-.05t.143-.036t.146-.021q.073-.008.147-.008t.147.008t.146.021q.072.015.143.036t.138.05q.068.028.133.063q.065.034.127.075q.061.041.118.088t.109.099l5.378 5.378q.052.052.099.109t.088.118t.075.127q.035.065.063.133q.029.068.05.138t.036.143q.014.073.021.146t.008.147t-.008.147q-.007.073-.021.146q-.015.072-.036.143t-.05.138q-.028.068-.063.133q-.034.065-.075.127q-.041.061-.088.118t-.099.109l-.193.193");
}

</style>
