<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irklkcfhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:amp-head" /></template>
<style>
.irklkcfhc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 6.75H18q1.76 0 3.005 1.245T22.25 11v5q0 1.76-1.245 3.005T18 20.25H6q-1.76 0-3.005-1.245T1.75 16v-5q0-1.76 1.245-3.005T6 6.75h1.75V5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h7q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146zm-7 0h5.5v-1h-5.5zm-4.5 6.75q0 2 2 2t2-2t-2-2t-2 2m7.25-2q-2 0-2 2t2 2t2-2t-2-2m3.25 2q0 2 2 2t2-2t-2-2t-2 2");
}

</style>
