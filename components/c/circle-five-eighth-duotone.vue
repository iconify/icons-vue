<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yjdw7wb-b"/><path class="g7v85mbik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-five-eighth-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g7v85mbik {
  d: path("M16.9498 7.0502C18.2154 8.3159 19 10.0672 19 12C19 15.8661 15.8661 19 12 19C10.1435 19 8.363 18.2625 7.0503 16.9497C6.8627 16.7621 6.7574 16.5078 6.7574 16.2426C6.7574 15.9774 6.8628 15.723 7.0503 15.5355L11 11.5858L11 6C11 5.4477 11.4477 5 12 5C13.9328 5 15.6841 5.7846 16.9498 7.0502Z");
}

.yjdw7wb-b {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12Z");
}

</style>
