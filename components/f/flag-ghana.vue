<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="wzk2vqbwb"/><path class="tgaq0cc9u"/><path class="o0758pb1r"/><path class="l8my59bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-ghana" /></template>
<style>
.l8my59bmm {
  d: path("m13.807 17.059l2.601 1.889L15.416 22l-.002.006l.009-.006l2.593-1.884L20.608 22l.009.006l-.002-.006l-.991-3.052l2.601-1.889H19.01L18.016 14l-.994 3.059z");
}

.o0758pb1r {
  fill: var(--svg-color--288541, #288541);
  d: path("M20.617 22.006L20.608 22h-5.186l-.009.006l.003-.006H0v5a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-5H20.615z");
}

.tgaq0cc9u {
  fill: var(--svg-color--fbd116, #fbd116);
  d: path("M15.423 22h5.185l-2.592-1.884zm3.587-4.941h3.215l-2.601 1.889l.991 3.052H36v-8H18.016zm-2.602 1.889l-2.601-1.889h3.215L18.016 14H0v8h15.416z");
}

.wzk2vqbwb {
  fill: var(--svg-color--cc212d, #cc212d);
  d: path("M32 5H4a4 4 0 0 0-4 4v5h36V9a4 4 0 0 0-4-4");
}

</style>
