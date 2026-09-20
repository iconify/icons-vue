<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="k2a4f3f-n"/><path class="twfn_7_ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:brotli" /></template>
<style>
.k2a4f3f-n {
  fill: var(--svg-color--ea3, #ea3);
  d: path("M94.88 251.608C26.612 233.316-13.9 163.146 4.391 94.879C22.684 26.613 92.854-13.9 161.121 4.392S269.9 92.854 251.608 161.121c-18.292 68.266-88.462 108.779-156.729 90.487");
}

.twfn_7_ac {
  fill: var(--svg-color--fff, #fff);
  d: path("M101.607 226.5c-13.6-3.644-12.809-50.698 1.768-105.098s37.418-95.547 51.018-91.902s12.809 50.698-1.768 105.098s-37.418 95.547-51.018 91.902m74.759-32.754c-6.8-1.822-6.404-25.35.884-52.55s18.71-47.773 25.51-45.95c6.8 1.822 6.404 25.349-.885 52.549s-18.709 47.773-25.509 45.95M53.24 160.755c-6.8-1.823-6.404-25.35.885-52.55s18.709-47.773 25.509-45.95c6.8 1.821 6.404 25.348-.884 52.548s-18.71 47.774-25.51 45.952");
}

</style>
