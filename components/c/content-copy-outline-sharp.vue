<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="julu32b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:content-copy-outline-sharp" /></template>
<style>
.julu32b1a {
  fill: currentColor;
  d: path("M7 18V2h13v16zm2-2h9V4H9zm-6 6V6h2v14h11v2zm6-6V4z");
}

</style>
