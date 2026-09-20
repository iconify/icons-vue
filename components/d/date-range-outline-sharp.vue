<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3edm76xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:date-range-outline-sharp" /></template>
<style>
.a3edm76xc {
  fill: currentColor;
  d: path("M7.46 13.655q-.23-.23-.23-.54t.23-.539t.54-.23t.54.23t.23.54t-.23.539t-.54.23t-.54-.23m4 0q-.23-.23-.23-.54t.23-.539t.54-.23t.54.23t.23.54t-.23.539t-.54.23t-.54-.23m4 0q-.23-.23-.23-.54t.23-.539t.54-.23t.54.23t.23.54t-.23.539t-.54.23t-.54-.23M4 21V5h3.385V2.77h1.077V5h7.154V2.77h1V5H20v16zm1-1h14v-9.384H5zM5 9.615h14V6H5zm0 0V6z");
}

</style>
