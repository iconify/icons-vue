<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y667-7b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:insert-edit" /></template>
<style>
.y667-7b2m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 4.25h2q2.5 0 2.5 2.5v2q0 2.5-2.5 2.5h-2q-2.5 0-2.5-2.5v-2q0-2.5 2.5-2.5m-6.25 8.5h2q2.5 0 2.5 2.5v2q0 .564-.127 1h5.754q-.127-.436-.127-1v-2q0-2.5 2.5-2.5h2q1.036 0 1.768.732t.732 1.768v2q0 .542-.201 1.002q.071.004.139.022t.133.048q.064.03.121.072t.105.093t.087.112t.064.125q.026.066.039.136q.013.069.013.14q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 19q0-.066.012-.131q.011-.066.034-.128t.056-.119q.034-.058.077-.108t.094-.093t.109-.074q.057-.033.12-.055q.062-.022.128-.032q-.13-.44-.13-1.01v-2q0-2.5 2.5-2.5");
}

</style>
