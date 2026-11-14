<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9ydm19ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:golden-spiral" /></template>
<style>
.c9ydm19ti {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 3.75H6q-1.76 0-3.005 1.245T1.75 8v8q0 .668.179 1.261q.639-3.86 3.555-6.777Q9.219 6.75 14.5 6.75q3.21 0 5.48 2.27t2.27 5.48q0 1.968-1.391 3.359T17.5 19.25q-3.25 0-3.25-3.25q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 1.75 1.75 1.75q3.25 0 3.25-3.25q0-2.589-1.831-4.419Q17.089 8.25 14.5 8.25q-4.66 0-7.955 3.295q-3.204 3.205-3.293 7.7Q4.418 20.25 6 20.25h12q1.76 0 3.005-1.245T22.25 16V8q0-1.76-1.245-3.005T18 3.75");
}

</style>
