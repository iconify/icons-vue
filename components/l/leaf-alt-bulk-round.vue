<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vsseiwmhu"/><path class="r5asrqbem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:leaf-alt-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r5asrqbem {
  d: path("M5.106 17.553c1.5-3.001 3.16-6.362 6.578-7.502a1.001 1.001 0 0 1 .632 1.898c-1.289.43-2.275 1.33-3.078 2.401a17 17 0 0 0-1.215 1.916c-.397.716-.763 1.449-1.129 2.181a11 11 0 0 0-.628 1.543c-.12.376-.22.76-.276 1.151a1 1 0 0 1-1.98-.282c.161-1.126.59-2.294 1.096-3.306");
}

.vsseiwmhu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 19a1 1 0 0 1-.707-.293c-.924-.924-1.644-2.045-2.005-3.307C3.06 14.6 3 13.826 3 13c0-2.744.854-5.296 2.97-7.131C8.658 3.542 12.57 3.001 16 3h4a1 1 0 0 1 1 1v2l-.002.057c-.203 3.534-1.062 7.328-3.646 9.916C15.106 18.219 12.103 18.999 9 19Z");
}

</style>
