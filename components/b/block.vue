<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="b0_86-aid"><path class="vn2yftyhm"/><path class="y0w8wxb-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:block" /></template>
<style>
.b0_86-aid {
  fill: var(--svg-color--2d338a, #2d338a);
}

.vn2yftyhm {
  d: path("M7.731 4.588H16.5L21 12l-4.5 7.412H7.654L12.077 12zm4.654 2.647L15.257 12l-2.872 4.765h2.572L17.811 12L14.94 7.235h-2.563z");
}

.y0w8wxb-l {
  d: path("M8.666 7.907L6.18 12l2.468 4.06l-1.577 2.635L3 12l4.106-6.761z");
}

</style>
