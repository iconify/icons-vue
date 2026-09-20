<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lowdwnyah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:key" /></template>
<style>
.lowdwnyah {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M68.53 76.78c5.56 2.87 11.86 4.53 18.55 4.53c22.3 0 40.38-18.08 40.38-40.38S109.38.55 87.08.55S46.69 18.63 46.69 40.93c0 6.69 1.65 12.99 4.53 18.54L29.39 81.3v11.54H17.85v11.53H6.3l-5.77 5.78v17.31h17.31zm18.55-47.4c0-6.37 5.16-11.54 11.54-11.54c6.37 0 11.53 5.16 11.53 11.54s-5.16 11.54-11.53 11.54c-6.38 0-11.54-5.16-11.54-11.54");
}

</style>
