<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuvzmybxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:balloons-bunch" /></template>
<style>
.cuvzmybxo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.435 2.314Q8.25 3.36 8.25 5.75q0 .679.096 1.249q-.688-.249-1.596-.249Q3 6.75 3 11q0 4.037 3.383 4.239l5.033 6.232h.001q.048.061.109.11l.001.001l.001.001h.001q.1.081.221.124t.25.043t.25-.043t.221-.124q.061-.048.11-.109l.002-.003h.001l5.033-6.232Q21 15.037 21 11q0-4.25-3.75-4.25q-.908 0-1.596.249q.096-.57.096-1.249q0-4.25-3.75-4.25q-1.642 0-2.565.814m3.315 16.564V9.953q.458-.062.846-.202q-.096.57-.096 1.249q0 3.352 2.333 4.06zm-1.5-8.925v8.925L8.167 15.06Q10.5 14.352 10.5 11q0-.679-.096-1.249q.388.14.846.202");
}

</style>
