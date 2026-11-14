<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6y7_eovw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lifting-hook" /></template>
<style>
.c6y7_eovw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 13.587V3.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 2.75 12 2.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V14q0 .099.026.194t.074.181q.05.086.12.155q.069.07.155.12q1.312.757 1.576 2.25q.263 1.492-.711 2.653T10 20.714t-2.49-1.161t-.711-2.653t1.576-2.25q.129-.075.22-.193t.129-.263q.039-.144.02-.292q-.02-.148-.094-.277q-.037-.064-.086-.12t-.107-.1t-.125-.078q-.067-.032-.138-.051q-.071-.02-.145-.024q-.074-.005-.147.004t-.143.034t-.134.06q-1.918 1.108-2.303 3.289q-.384 2.182 1.039 3.878T10 22.214t3.639-1.697q1.423-1.696 1.039-3.878q-.346-1.959-1.928-3.052");
}

</style>
