<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="naghcvb4j"/><path class="i2owb1n5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flask-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i2owb1n5a {
  d: path("M8 4a1 1 0 0 1 0-2h8a1 1 0 0 1 0 2ZM7 14h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

.naghcvb4j {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 2h4a1 1 0 0 1 1 1v5.764l3.894 7.789c.56 1.12.597 2.457.034 3.583a3.44 3.44 0 0 1-1.154 1.328A3.2 3.2 0 0 1 16 22H8a3.2 3.2 0 0 1-1.774-.536a3.44 3.44 0 0 1-1.154-1.328c-.563-1.126-.526-2.463.034-3.583L9 8.764V3a1 1 0 0 1 1-1");
}

</style>
