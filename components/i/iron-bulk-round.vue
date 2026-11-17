<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uosgmn40i"/><path class="od35trtci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:iron-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.od35trtci {
  d: path("M19 7h-2a.997.997 0 0 0-1 1v3a1 1 0 0 1-2 0V7.999c0-.796.317-1.56.881-2.122A3 3 0 0 1 17 5h2a3.004 3.004 0 0 1 3 3v3a1 1 0 0 1-2 0V7.999A1 1 0 0 0 19 7");
}

.uosgmn40i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 14a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 19H5c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186l5-5C9.252 10.335 10.683 10 12 10h9a1 1 0 0 1 1 1Z");
}

</style>
