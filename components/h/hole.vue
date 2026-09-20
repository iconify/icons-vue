<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="n5d8job_s"/><path class="vsixkn4xl"/><path class="zk1tkpb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:hole" /></template>
<style>
.n5d8job_s {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M18 11.001c-9.389 0-17 3.358-17 7.5s7.611 7.5 17 7.5s17-3.358 17-7.5s-7.611-7.5-17-7.5");
}

.vsixkn4xl {
  fill: var(--svg-color--7d8b93, #7d8b93);
  d: path("M33.871 19.284c.079-.256.129-.516.129-.783c0-1.418-1.16-2.676-3-3.699v2.778c1.083.51 2.05 1.08 2.871 1.704M5 14.802c-1.84 1.023-3 2.281-3 3.699c0 .267.05.527.129.783C2.95 18.66 3.917 18.09 5 17.58z");
}

.zk1tkpb7n {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M18 12.001c-4.766 0-9.87 1.06-13 2.801v2.778c3.398-1.598 7.967-2.579 13-2.579s9.602.981 13 2.579v-2.778c-3.13-1.741-8.234-2.801-13-2.801");
}

</style>
