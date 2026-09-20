<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke57yc_7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:carry-on-bag-checked-sharp" /></template>
<style>
.ke57yc_7w {
  fill: currentColor;
  d: path("m17.3 20.25l3.55-3.55l-.75-.75l-2.8 2.8l-1.4-1.4l-.75.75zm-2.838 1.288Q13 20.075 13 18t1.463-3.537T18 13t3.538 1.463T23 18t-1.463 3.538T18 23t-3.537-1.463M10.5 21V7H14V4h-2V2h4v9.3q-2.225.725-3.613 2.55T11 18q0 .8.175 1.538T11.7 21zM6 21V7h3v14z");
}

</style>
