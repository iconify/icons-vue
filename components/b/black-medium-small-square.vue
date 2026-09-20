<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="znanlqasi"/><path class="l_ct7jbcg"/><path class="w3yvtwbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:black-medium-small-square" /></template>
<style>
.l_ct7jbcg {
  fill: var(--svg-color--424242, #424242);
  d: path("M30.403 26.506H91.42a3.9 3.9 0 0 1 3.898 3.898V91.42a3.9 3.9 0 0 1-3.898 3.898H30.403a3.9 3.9 0 0 1-3.898-3.898V30.538a3.847 3.847 0 0 1 3.656-4.032c.08 0 .161-.013.242 0");
}

.w3yvtwbuo {
  fill: var(--svg-color--787878, #787878);
  d: path("M53.654 32.554c0-2.016-1.344-2.554-9.274-2.285c-6.585.269-9.811 1.075-11.827 3.494s-2.554 7.258-2.554 13.171c0 4.167 0 7.93 2.15 7.93c2.958 0 2.958-6.72 5.377-10.618c4.435-7.391 16.128-9.004 16.128-11.692");
}

.znanlqasi {
  fill: var(--svg-color--575757, #575757);
  d: path("M30.403 26.506h67.2a3.9 3.9 0 0 1 3.897 3.898v67.198a3.9 3.9 0 0 1-3.898 3.898h-67.2a3.9 3.9 0 0 1-3.897-3.898V30.538a3.847 3.847 0 0 1 3.656-4.032c.08 0 .161-.013.242 0");
}

</style>
