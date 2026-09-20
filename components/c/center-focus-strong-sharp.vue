<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvul-iaug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:center-focus-strong-sharp" /></template>
<style>
.cvul-iaug {
  fill: currentColor;
  d: path("M8.463 15.538Q7 14.075 7 12t1.463-3.537T12 7t3.538 1.463T17 12t-1.463 3.538T12 17t-3.537-1.463M3 21v-6h2v4h4v2zm12 0v-2h4v-4h2v6zM3 9V3h6v2H5v4zm16 0V5h-4V3h6v6z");
}

</style>
