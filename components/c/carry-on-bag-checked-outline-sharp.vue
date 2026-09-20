<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-kbmubef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:carry-on-bag-checked-outline-sharp" /></template>
<style>
.g-kbmubef {
  fill: currentColor;
  d: path("m17.3 20.25l3.55-3.55l-.75-.75l-2.8 2.8l-1.4-1.4l-.75.75zM9 19V9H8v10zm2.7 2H6V7h8V4h-2V2h4v9.3q-.6.2-1.037.4t-.963.55V9h-3v10h.1q.075.6.225 1.05t.375.95m9.838-6.538Q23 15.926 23 18t-1.463 3.538T18 23t-3.537-1.463T13 18t1.463-3.537T18 13t3.538 1.463M9 19V9zm2 0V9z");
}

</style>
