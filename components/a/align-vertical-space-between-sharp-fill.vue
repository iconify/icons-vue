<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sc-pntbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-space-between-sharp-fill" /></template>
<style>
.sc-pntbko {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 5V9C6 9.5523 6.448 10 7 10H17C17.552 10 18 9.5523 18 9V5H23V3H1V5H6ZM6 19V15C6 14.4477 6.448 14 7 14H17C17.552 14 18 14.4477 18 15V19H23V21H1V19H6Z");
}

</style>
