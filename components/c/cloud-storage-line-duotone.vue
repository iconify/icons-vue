<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gwj2w_bps"/><path class="q7aor7big"/><path class="cehgcdc1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-storage-line-duotone" /></template>
<style>
.cehgcdc1k {
  stroke-linejoin: round;
  d: path("M11 18H13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gwj2w_bps {
  d: path("M6.28571 18C3.91878 18 2 16.1038 2 13.7647C2 11.4256 3.91878 9.52941 6.28571 9.52941C6.56983 9.52941 6.8475 9.55673 7.11616 9.60887M17.5 17.8722C20.0726 17.3221 22 15.0599 22 12.3529C22 9.88113 20.393 7.78024 18.1551 7.01498C17.5693 6.81468 16.9404 6.70588 16.2857 6.70588C15.6178 6.70588 14.9767 6.81911 14.381 7.02721M7.11616 9.60887C6.88706 8.9978 6.7619 8.33687 6.7619 7.64706C6.7619 4.52827 9.32028 2 12.4762 2C15.4159 2 17.8371 4.19371 18.1551 7.01498M7.11616 9.60887C7.68058 9.71839 8.20528 9.9374 8.66667 10.2426");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q7aor7big {
  d: path("M11.5 22H12.5C13.9142 22 14.6213 22 15.0607 21.5607C15.5 21.1213 15.5 20.4142 15.5 19V17C15.5 15.5858 15.5 14.8787 15.0607 14.4393C14.6213 14 13.9142 14 12.5 14H11.5C10.0858 14 9.37868 14 8.93934 14.4393C8.5 14.8787 8.5 15.5858 8.5 17V19C8.5 20.4142 8.5 21.1213 8.93934 21.5607C9.37868 22 10.0858 22 11.5 22Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
