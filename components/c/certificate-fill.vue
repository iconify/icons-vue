<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvckbdcgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:certificate-fill" /></template>
<style>
.xvckbdcgm {
  fill: currentColor;
  d: path("M2 15V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v12a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1H5a.997.997 0 0 0-1 1v10a1 1 0 0 0 1 1h4a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3m15-9a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm1 15a1.002 1.002 0 0 1-1.707.707L15 20.414l-1.293 1.293A1 1 0 0 1 12 21v-5.62a3.828 3.828 0 0 1 5.601-5.189A3.83 3.83 0 0 1 18 15.38ZM9 10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

</style>
