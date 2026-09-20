<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oqhm75b2i"/><path class="wk5vw_5qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:gordon" /></template>
<style>
.oqhm75b2i {
  d: path("M256 128c0 70.692-57.308 128-128 128C57.308 256 0 198.692 0 128C0 57.308 57.308 0 128 0c70.692 0 128 57.308 128 128");
  fill: var(--svg-color--3e4349, #3E4349);
}

.wk5vw_5qg {
  d: path("M86.99 81.79V61.61c43.244-7.352 41.947 8.936 55.929 44.108c4.854 12.209 17.298 47.568 24.937 64.576c1.73 6.054 5.3 5.767 11.244 4.18v17.587c-14.425 6.487-30.847 6.438-35.076-9.322l-16.096-49.346l-21.766 60.254H76.9l38.487-88.794c-1.94-6.302-5.17-13.28-8.937-20.54c-3.316-6.127-12.83-5.502-19.46-2.523");
  fill: var(--svg-color--fff, #FFF);
}

</style>
