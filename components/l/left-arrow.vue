<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ce44osb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:left-arrow" /></template>
<style>
.ce44osb2z {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("m22.95 64l42.46-31.14v19.42h39.64v23.23H65.41v19.61z");
}

</style>
