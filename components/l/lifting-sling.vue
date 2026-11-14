<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="but7ig8bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lifting-sling" /></template>
<style>
.but7ig8bm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.75 2.5v4q0 1.89-1.299 2.481l3.881 4.269h.543q3.375 0 3.375 3.375v2.25q0 3.375-3.375 3.375H6.125q-3.375 0-3.375-3.375v-2.25q0-3.375 3.375-3.375h.543l3.881-4.269Q9.25 8.39 9.25 6.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T10 5.75t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 1.25 1.249 1.25H12q1.25 0 1.25-1.25v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146M12 9.615l3.305 3.635h-6.61z");
}

</style>
