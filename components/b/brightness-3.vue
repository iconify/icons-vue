<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td498mbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:brightness-3" /></template>
<style>
.td498mbxq {
  fill: currentColor;
  d: path("M9 22q-.8 0-1.537-.112T6 21.55q3.15-1.025 5.075-3.65T13 12t-1.925-5.9T6 2.45q.725-.225 1.463-.337T9 2q2.075 0 3.9.788t3.175 2.137T18.213 8.1T19 12t-.788 3.9t-2.137 3.175t-3.175 2.138T9 22");
}

</style>
