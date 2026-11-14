<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pan9c2gyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:layers-merge" /></template>
<style>
.pan9c2gyz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.386 7.643q-.029.017-.059.032q-.084.041-.175.06q-.092.018-.185.014q-.094-.004-.183-.031q-.09-.027-.17-.075l-7.5-4.5q-.063-.038-.118-.088t-.099-.109t-.075-.126q-.032-.066-.05-.138t-.021-.146t.007-.146t.036-.143t.063-.133t.088-.118t.109-.099t.126-.075t.138-.05t.146-.021q.073-.004.146.007t.143.036t.133.063L12 6.125l7.114-4.268q.063-.038.133-.063t.143-.036t.146-.007q.074.003.146.021t.138.05t.126.075t.109.099t.088.118t.063.133t.036.143q.011.073.007.146q-.003.074-.021.146t-.05.138q-.031.067-.075.126q-.044.06-.099.109q-.055.05-.118.088zm.781 2.625l5.251 2.771q1.334.703 1.334 2.211t-1.334 2.211l-5.251 2.771q-1.167.616-2.334 0l-5.251-2.771q-1.334-.703-1.334-2.211t1.334-2.211l5.251-2.771q1.167-.616 2.334 0");
}

</style>
