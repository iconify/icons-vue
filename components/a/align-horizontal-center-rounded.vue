<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8m--ubtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-horizontal-center-rounded" /></template>
<style>
.d8m--ubtg {
  fill: currentColor;
  d: path("M11.5 20.5v-4.192H8.02q-.414 0-.717-.303T7 15.289t.303-.717t.716-.303H11.5V9.731H5.02q-.414 0-.717-.303T4 8.711t.303-.716t.716-.303H11.5V3.5q0-.213.143-.357T12 3t.357.143t.143.357v4.192h6.48q.414 0 .717.303t.303.716t-.303.717t-.716.303H12.5v4.538h3.48q.414 0 .717.303t.303.716t-.303.717t-.716.303H12.5V20.5q0 .214-.143.357T12 21t-.357-.143t-.143-.357");
}

</style>
