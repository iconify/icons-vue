<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="xj28t7van"/><path class="ty2a9kbnk"/><path class="oq_o124bb"/><path class="yc_xi1bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-ghana" /></template>
<style>
.oq_o124bb {
  fill: var(--svg-color--288541, #288541);
  d: path("M20.617 22.006L20.608 22h-5.186l-.009.006l.003-.006H0v5a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-5H20.615l.002.006z");
}

.ty2a9kbnk {
  fill: var(--svg-color--fbd116, #FBD116);
  d: path("M15.423 22h5.185l-2.592-1.884zm3.587-4.941h3.215l-2.601 1.889l.991 3.052H36v-8H18.016zm-2.602 1.889l-2.601-1.889h3.215L18.016 14H0v8h15.416z");
}

.xj28t7van {
  fill: var(--svg-color--cc212d, #CC212D);
  d: path("M32 5H4a4 4 0 0 0-4 4v5h36V9a4 4 0 0 0-4-4z");
}

.yc_xi1bis {
  d: path("M13.807 17.059l2.601 1.889L15.416 22l-.002.006l.009-.006l2.593-1.884L20.608 22l.009.006l-.002-.006l-.991-3.052l2.601-1.889H19.01L18.016 14l-.994 3.059z");
  fill: var(--svg-color--000, #000);
}

</style>
