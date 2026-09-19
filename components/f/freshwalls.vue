<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ibuf4geni"/><path class="n6jqjab-u"/><path class="djlk_8rul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freshwalls" /></template>
<style>
.djlk_8rul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.063 20.445l3.27 3.624l3.624-3.978l3.359 3.978l3.447-3.878");
}

.ibuf4geni {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.389 10.545h11.049c.707 0 1.326.619 1.326 1.326v20.86c0 .707-.62 1.326-1.326 1.326h-11.05c-.706 0-1.325-.619-1.325-1.326v-20.86c0-.707.619-1.326 1.326-1.326");
}

.n6jqjab-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.675 34.057l5.237 3.005c.708.442 1.68.177 2.122-.53l10.253-17.678c.442-.619.177-1.591-.619-2.033l-9.192-5.304c-.707-.442-1.68-.176-2.122.53l-1.59 2.74m-13.701-.063l-1.503-2.588c-.442-.707-1.414-.972-2.121-.53l-9.193 5.303c-.707.442-.972 1.414-.53 2.122L13.97 36.709c.442.707 1.414.972 2.122.53l5.391-3.094");
}

</style>
