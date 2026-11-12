<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aec7lkj0a"/><path class="b_dy2secm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-angry-bulk-sharp" /></template>
<style>
.aec7lkj0a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.196 21.981a1 1 0 0 1-1.177-1.177l.935-4.673A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046Z");
}

.b_dy2secm {
  d: path("M10.447 9.106a1 1 0 1 1-.894 1.788l-2-1a1 1 0 1 1 .894-1.788Zm4 1.788a1 1 0 1 1-.894-1.788l2-1a1 1 0 1 1 .894 1.788Zm-4.951 1.937A6.6 6.6 0 0 1 12 12.343a6.6 6.6 0 0 1 2.504.488a6.6 6.6 0 0 1 2.203 1.462a.997.997 0 0 1 0 1.414a1 1 0 0 1-1.414 0A4.63 4.63 0 0 0 12 14.343a4.64 4.64 0 0 0-3.293 1.364a.999.999 0 1 1-1.414-1.414a6.6 6.6 0 0 1 2.203-1.462");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
