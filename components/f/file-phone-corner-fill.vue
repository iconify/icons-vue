<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_r268bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-phone-corner-fill" /></template>
<style>
.d_r268bqf {
  fill: currentColor;
  d: path("M10 11v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10h-8a.997.997 0 0 0-1 1m7-3l-4-4v2a2 2 0 0 0 2 2Zm-3.111 4h1.333c.765 0 1.581.357 1.838 1.128l.444 1.334c.239.716-.195 1.42-.686 1.912l-.182.182l.808.808l.182-.182c.492-.491 1.196-.925 1.912-.686l1.334.444c.771.257 1.128 1.073 1.128 1.838v1.333A1.89 1.89 0 0 1 20.111 22a8 8 0 0 1-3.157-.638a8 8 0 0 1-2.578-1.738a8 8 0 0 1-1.738-2.578A8 8 0 0 1 12 13.889A1.89 1.89 0 0 1 13.889 12");
}

</style>
