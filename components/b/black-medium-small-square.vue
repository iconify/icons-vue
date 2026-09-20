<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k9jca4tfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:black-medium-small-square" /></template>
<style>
.k9jca4tfl {
  fill: var(--svg-color--212121, #212121);
  d: path("M40.03 40.02h47.95v47.95H40.03z");
}

</style>
