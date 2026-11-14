<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzy_bcbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-cycling" /></template>
<style>
.qzy_bcbhp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.425 7.25H16q.062 0 .124.01q.061.011.12.031t.114.05q.054.03.104.068t.091.084q.042.046.076.098t.059.11t.04.117l.861 3.448q.203-.016.411-.016q1.968 0 3.359 1.391T22.75 16t-1.391 3.359T18 20.75t-3.359-1.391T13.25 16t1.391-3.359q.677-.677 1.49-1.024l-.717-2.867h-4.95l-1.693 3.385q.306.224.588.506Q10.75 14.032 10.75 16t-1.391 3.359T6 20.75t-3.359-1.391T1.25 16t1.391-3.359T6 11.25q.759 0 1.433.207l1.712-3.424l-1.288-2.147q-.038-.063-.063-.133t-.036-.143t-.007-.146t.021-.146q.018-.072.05-.138q.031-.067.075-.126q.044-.06.099-.109q.055-.05.118-.088q.178-.107.386-.107h3q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H9.825z");
}

</style>
