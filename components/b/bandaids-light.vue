<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rvpam9b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bandaids-light" /></template>
<style>
.rvpam9b-x {
  fill: currentColor;
  d: path("m181.74 128l29.13-29.13a38 38 0 1 0-53.74-53.74L128 74.26L98.87 45.13a38 38 0 1 0-53.74 53.74L74.26 128l-29.13 29.13a38 38 0 1 0 53.74 53.74L128 181.74l29.13 29.13a38 38 0 1 0 53.74-53.74Zm-16.12-74.38a26 26 0 1 1 36.76 36.77l-29.13 29.13l-36.76-36.77Zm-.85 74.38L128 164.77L91.23 128L128 91.23ZM53.62 90.38a26 26 0 1 1 36.76-36.76l29.13 29.13l-36.76 36.77Zm36.76 112a26 26 0 1 1-36.76-36.76l29.13-29.13l36.76 36.76Zm112 0a26 26 0 0 1-36.76 0l-29.14-29.13l36.77-36.77l29.13 29.14a26 26 0 0 1 0 36.76M118 128a10 10 0 1 1 10 10a10 10 0 0 1-10-10");
}

</style>
