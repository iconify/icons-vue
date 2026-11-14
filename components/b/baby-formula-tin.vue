<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2fk6h_ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-formula-tin" /></template>
<style>
.p2fk6h_ve {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 7q0-3 6.75-3t6.75 3v8.5h-1.5v-3.338Q12.568 13 9 13t-5.25-.838V18.5Q3.75 20 9 20q2.226 0 3.509-.27q.341.677.91 1.26q-1.635.51-4.419.51q-6.75 0-6.75-3zm12 3v-.838Q12.568 10 9 10t-5.25-.838V10q0 1.5 5.25 1.5t5.25-1.5M17 21.25q3.677 0 3.749-3.606l1.7-4.372q.054-.139.051-.288q-.003-.15-.064-.286q-.06-.137-.167-.24t-.247-.157q-.069-.027-.142-.04q-.073-.012-.146-.011q-.074.002-.146.018t-.14.046t-.128.072q-.061.042-.112.095q-.051.054-.091.116q-.039.062-.066.131l-1.564 4.022H14q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 3.75 3.75 3.75m-2.174-3h4.348q-.337 1.5-2.174 1.5t-2.174-1.5");
}

</style>
