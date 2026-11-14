<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvk94z7yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dental-probe" /></template>
<style>
.gvk94z7yd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m16.47 6.47l1.75-1.75q.44-.44.486-.686q-.597-.214-1.055.588q-.036.064-.085.12q-.048.056-.107.101t-.124.078q-.066.033-.138.053q-.071.019-.145.024q-.073.005-.147-.004q-.073-.009-.143-.033q-.07-.023-.134-.06q-.13-.074-.221-.192t-.131-.262t-.02-.292q.019-.148.093-.277q1.108-1.939 2.923-1.233q.963.374.939 1.377q-.021.848-.931 1.758l-1.75 1.75l-6.559 6.56q.193.415.193.91q0 .897-.634 1.53l-3.5 3.5q-.633.634-1.53.634t-1.53-.634q-.634-.633-.634-1.53q0-.896.634-1.53l3.5-3.5q.633-.634 1.53-.634q.495 0 .91.193z");
}

</style>
