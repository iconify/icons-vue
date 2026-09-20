<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tao24g5lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-charging-90-outline-sharp" /></template>
<style>
.tao24g5lr {
  fill: currentColor;
  d: path("M7.885 21V4.48h2.423V3h3.384v1.48h2.424v7.712q-2.135.275-3.587 1.898t-1.452 3.852q0 .843.227 1.618t.663 1.44zm1-13.154h6.23V5.461h-6.23zm7.692 13.635v-2.635h-1.539l2.385-4.327v2.635h1.539z");
}

</style>
