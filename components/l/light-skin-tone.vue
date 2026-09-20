<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="z-3stebpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:light-skin-tone" /></template>
<style>
.z-3stebpd {
  fill: var(--svg-color--fadcbc, #fadcbc);
  d: path("M10 10h108v108H10z");
}

</style>
