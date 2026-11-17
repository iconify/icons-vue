<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u_8fa3j-i"/><path class="df8w3-fyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-3-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.df8w3-fyp {
  d: path("M6 4a1 1 0 0 1 1-1h8a5 5 0 0 1 5 5v11h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1v-4.078a5 5 0 0 1 1.876-3.904L6 10.919Zm7.124 6.218l1 .8A5 5 0 0 1 16 14.922V19h2V8a3 3 0 0 0-3-3H8v4.539a5 5 0 0 1 5.124.679M7.126 12.58A3 3 0 0 0 6 14.922V19h8v-4.078c0-.911-.414-1.773-1.126-2.342l-1-.8a3 3 0 0 0-3.748 0Z");
}

.u_8fa3j-i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 21H7a1 1 0 0 1-1-1V8a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v12a1 1 0 0 1-1 1");
}

</style>
