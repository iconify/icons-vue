<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mh94iq3tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:farlight-84" /></template>
<style>
.mh94iq3tf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.071 13.845l6.006-6.4l-23.436-.169l-.489 1.986l-8.652.532l10.313 2.699l.017-1.27zm-15.384 3.843l-8.545-2.002l11.572 20.38l1.964-.569l4.787 7.227l-2.82-10.281l-1.107.62zm11.02 11.401l2.539 8.401L41.11 17.279l-1.475-1.417L43.5 8.103l-7.494 7.582l1.092.649zM22.911 25l6.385-6.248l-8.603-2.405z");
}

</style>
