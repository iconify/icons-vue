<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi9b599qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:highlighter-size-3-outline-sharp" /></template>
<style>
.fi9b599qb {
  fill: currentColor;
  d: path("m7.75 19.75l-3.525-3.525q-.275-.275-.275-.7t.275-.7L14.8 4.225q.3-.3.725-.3t.7.3l3.525 3.55q.275.275.275.7t-.275.7L9.175 19.75q-.3.3-.712.3t-.713-.3");
}

</style>
