<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo5u-_v_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-9-outline-sharp" /></template>
<style>
.xo5u-_v_g {
  fill: currentColor;
  d: path("M12 15h5V5h-6v6h4v2h-3zm3-6h-2V7h2zm-9 9V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zm6-6V4z");
}

</style>
