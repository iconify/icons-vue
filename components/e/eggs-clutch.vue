<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4a9kmcwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eggs-clutch" /></template>
<style>
.q4a9kmcwe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.509 11.25h-1.264q-.1-7.5-2.245-7.5t-2.245 7.5H8.491q-.13-5.5-2.241-5.5t-2.241 5.5H3q-.037 0-.075.004q-.073.007-.144.029q-.07.021-.136.056q-.065.035-.122.082t-.103.104t-.082.122t-.056.136t-.028.145q-.008.073 0 .147q.391 3.916 3.289 6.144Q8.182 20.25 12 20.25t6.457-2.031q2.898-2.228 3.289-6.144q.004-.038.004-.075q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 11.25h-1.009q-.13-5.5-2.241-5.5t-2.241 5.5m1.496 0h1.49q-.057-4-.745-4t-.745 4m-4.707-4.53q.397 1.855.445 4.53h-1.486q.048-2.675.445-4.53q.139-.651.298-1.068q.159.417.298 1.068m-5.303 4.53q-.057-4-.745-4t-.745 4z");
}

</style>
