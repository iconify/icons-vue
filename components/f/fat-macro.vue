<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev8w7fywk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fat-macro" /></template>
<style>
.ev8w7fywk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.479 2.461l-.018.018Q4 10.197 4 14.25q0 3.314 2.343 5.657T12 22.25t5.657-2.343T20 14.25q0-4.053-7.461-11.771q-.051-.053-.112-.095t-.128-.072t-.14-.045t-.146-.017t-.147.012t-.141.04t-.131.067t-.115.092m5.217 14.319q-.028.069-.068.13q-.041.062-.092.115q-.052.053-.113.094q-.061.042-.129.071t-.14.044t-.147.016q-.073.001-.146-.013t-.141-.041q-.069-.028-.13-.068q-.062-.041-.115-.092q-.053-.052-.094-.113q-.042-.061-.071-.129t-.044-.14t-.016-.147q-.001-.073.013-.146t.041-.141q.593-1.472-.203-2.844q-.037-.064-.061-.134t-.033-.143t-.005-.147t.023-.145t.052-.138t.077-.125t.1-.107t.12-.086t.134-.061t.143-.033t.147-.005t.145.023t.138.052q.066.032.125.077t.107.1q.049.056.086.12q1.163 2.006.297 4.156");
}

</style>
