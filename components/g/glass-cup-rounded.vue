<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du2wotb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:glass-cup-rounded" /></template>
<style>
.du2wotb0v {
  fill: currentColor;
  d: path("M6.975 22q-.775 0-1.337-.5T5 20.225L3.275 4.475q-.125-1 .55-1.737T5.5 2h13q1 0 1.675.738t.55 1.737L19 20.225q-.075.775-.638 1.275t-1.337.5zm-.4-6H17.45l1.3-12H5.25z");
}

</style>
