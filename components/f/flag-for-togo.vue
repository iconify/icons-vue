<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jvoxrvbzc"/><path class="z9s325u2x"/><path class="r5qsoip_g"/><path class="kt_o4tuli"/><path class="hu_gnckyd"/><path class="hkar_pbyl"/><path class="hvwtgtbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-togo" /></template>
<style>
.hkar_pbyl {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M61.4 26H32v12h29.4q.6-2.85.6-6c0-3.15-.2-4.1-.6-6");
}

.hu_gnckyd {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M56 14H32v12h29.4c-.9-4.4-2.8-8.5-5.4-12");
}

.hvwtgtbbh {
  fill: var(--svg-color--fff, #fff);
  d: path("m18 27.3l6.8 4.7l-2.6-7.6l6.8-4.8h-8.4L18 12l-2.6 7.6H7l6.8 4.8l-2.6 7.6z");
}

.jvoxrvbzc {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M8 50h48c2.6-3.5 4.5-7.6 5.4-12H2.6c.9 4.4 2.8 8.5 5.4 12");
}

.kt_o4tuli {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M32 2v12h24C50.5 6.7 41.8 2 32 2");
}

.r5qsoip_g {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M2 32q0 3.15.6 6H32V2C15.4 2 2 15.4 2 32");
}

.z9s325u2x {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M56 50H8c5.5 7.3 14.2 12 24 12s18.5-4.7 24-12");
}

</style>
