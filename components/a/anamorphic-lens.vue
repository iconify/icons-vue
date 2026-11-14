<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg73k6blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anamorphic-lens" /></template>
<style>
.gg73k6blo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.493 5.67q-.49 1.041-.787 2.245q-.833-.665-2.331-.665h-3.75q-3.375 0-3.375 3.375v2.75q0 1.398.989 2.386q.988.989 2.386.989h3.75q1.323 0 2.279-.885q.305 1.329.839 2.465q1.374 2.92 3.507 2.92t3.507-2.92q1.115-2.369 1.23-5.58H14.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h6.237q-.115-3.211-1.23-5.58Q18.133 2.75 16 2.75t-3.507 2.92");
}

</style>
