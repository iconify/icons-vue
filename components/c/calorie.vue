<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5uly4bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:calorie" /></template>
<style>
.d5uly4bth {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m10.748-4.061q-.052-.046-.112-.082q-.063-.038-.133-.063t-.143-.036t-.146-.007q-.074.003-.146.021t-.138.05q-.067.031-.126.075q-.06.044-.109.099q-.05.055-.088.118q-.473.789-.594 2.088q-.046-.043-.099-.077q-.052-.035-.11-.061t-.119-.041t-.123-.02q-.063-.006-.126 0q-.063.005-.124.021t-.118.041t-.11.061Q8.25 11.182 8.25 13.25Q8.25 17 12 17t3.75-3.75q0-2.42-3.252-5.311");
}

</style>
