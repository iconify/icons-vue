<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="fj_lrl_tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:letter-l" /></template>
<style>
.fj_lrl_tp {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.792 9.156c0-1.55.992-2.418 2.325-2.418s2.325.868 2.325 2.418V24.72h5.52c1.58 0 2.263 1.179 2.232 2.232c-.061 1.025-.868 2.048-2.231 2.048H15.21c-1.519 0-2.418-.992-2.418-2.543z");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
