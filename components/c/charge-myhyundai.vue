<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="uggqlovfk"/><path class="l0caveb_j"/><circle class="znvb6lbhz"/><path class="cdvhvjbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:charge-myhyundai" /></template>
<style>
.cdvhvjbme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.866 20.784l-1.458-8.161a1 1 0 0 0-.985-.824h-15.36a1 1 0 0 0-.984.824l-1.458 8.16zm6.678-8.985H42.5v4.797a1.59 1.59 0 0 1-1.59 1.59h-3.776a1.59 1.59 0 0 1-1.59-1.59zm1.393-3.534v3.534m4.169 0V8.265m-2.084 9.921v19.959a1.59 1.59 0 0 1-1.59 1.59H20.333a1.59 1.59 0 0 1-1.59-1.59v-6.592");
}

.l0caveb_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.807 20.784a3.18 3.18 0 0 1 3.18 3.18v9.543a1.59 1.59 0 0 1-1.59 1.59h-1.836a1.59 1.59 0 0 1-1.59-1.59v-1.954H10.517v1.954a1.59 1.59 0 0 1-1.59 1.59H7.09a1.59 1.59 0 0 1-1.59-1.59v-9.542a3.18 3.18 0 0 1 3.18-3.181");
}

.uggqlovfk {
  cx: 11.13px;
  cy: 26.168px;
  r: 2.296px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.znvb6lbhz {
  cx: 26.358px;
  cy: 26.168px;
  r: 2.296px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
