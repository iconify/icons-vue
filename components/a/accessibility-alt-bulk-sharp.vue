<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ki6vkl7df"/><path class="brht7lb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:accessibility-alt-bulk-sharp" /></template>
<style>
.brht7lb0a {
  d: path("M12 9h7a1 1 0 0 1 0 2h-6v2.697l3.832 5.748a1 1 0 0 1-1.664 1.11L12 15.803l-3.168 4.752a1 1 0 0 1-1.664-1.11L11 13.697V11H5a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ki6vkl7df {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.158 4.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
