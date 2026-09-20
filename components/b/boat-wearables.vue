<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qvs9xfk5v"/><path class="y9kswnbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:boat-wearables" /></template>
<style>
.qvs9xfk5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.72 22.85c1.18 11.51-7.253 21.604-18.837 22.548S3.953 37.775 2.772 26.266C1.592 14.756 10.025 4.662 21.609 3.72A21.47 21.47 0 0 1 33.3 6.11m4.69 1.2za1.37 1.37 0 0 1 1.88.43l5.22 8.33a1.37 1.37 0 0 1-.429 1.89h-.001a1.37 1.37 0 0 1-1.88-.44l-5.22-8.33a1.37 1.37 0 0 1 .43-1.88");
}

.y9kswnbgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.1 35.6l-13.78.12l-2.76-5.75l19.65.1zm-6.5-23.29l4.97 13.28l-10.83 3.31z");
}

</style>
