<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chfie0-2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:category-search-sharp" /></template>
<style>
.chfie0-2r {
  fill: currentColor;
  d: path("M3 19.5v-6.462h6.462V19.5zM7.115 9l4.116-6.77L15.346 9zm14.499 12.835l-2.612-2.612q-.467.37-1.041.573q-.574.204-1.23.204q-1.567 0-2.65-1.082T13 16.27t1.082-2.649t2.649-1.082t2.649 1.082t1.082 2.65q0 .65-.204 1.214t-.548 1.031l2.611 2.612zm-2.945-3.627q.793-.792.793-1.939t-.793-1.938t-1.938-.793t-1.939.793T14 16.269t.792 1.939t1.939.792t1.938-.792");
}

</style>
