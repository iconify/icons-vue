<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edfx_teni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grid-off-outline-sharp" /></template>
<style>
.edfx_teni {
  fill: currentColor;
  d: path("M8.998 19v-3.998H5V19zm5.004 0v-3.577l-.421-.421H9.998V19zm-5.004-4.998v-3.583l-.421-.421H5v4.004zm10.002 0V9.998h-3.998v2.187l1.817 1.817zm-4.998-5.004V5H9.998v2.18l1.818 1.818zm4.998 0V5h-3.998v3.998zm1 8.185L6.817 4H20zM4 20V4l16 16zm17.11 2.53L1.892 3.309L2.6 2.6l19.223 19.223z");
}

</style>
