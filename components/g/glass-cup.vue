<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxo_u_b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:glass-cup" /></template>
<style>
.yxo_u_b3g {
  fill: currentColor;
  d: path("M7.475 21q-.621 0-1.087-.404q-.467-.404-.522-1.025L4 3h16l-1.846 16.571q-.056.621-.522 1.025T16.544 21zm-.938-4.5h10.952L18.866 4H5.116z");
}

</style>
