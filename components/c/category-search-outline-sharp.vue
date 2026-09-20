<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s59ovsb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:category-search-outline-sharp" /></template>
<style>
.s59ovsb8a {
  fill: currentColor;
  d: path("M3 19.5v-6.462h6.462V19.5zm1-1h4.462v-4.462H4zM7.115 9l4.116-6.77L15.346 9zm1.743-1h4.746L11.23 4.196zm12.756 13.835l-2.612-2.612q-.467.37-1.041.573q-.574.204-1.23.204q-1.567 0-2.65-1.082T13 16.27t1.082-2.649t2.649-1.082t2.649 1.082t1.082 2.65q0 .65-.204 1.214t-.548 1.031l2.611 2.612zm-2.945-3.627q.793-.792.793-1.939t-.793-1.938t-1.938-.793t-1.939.793T14 16.269t.792 1.939t1.939.792t1.938-.792M11.231 8");
}

</style>
