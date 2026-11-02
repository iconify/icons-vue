<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ie_ydxblm"/><path class="dfaxbqgfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bulb-sparkle-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dfaxbqgfu {
  d: path("M8.989 7.999c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375L11 5.986a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177l.003.001a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375l-.001.003a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L8.986 10a1 1 0 0 1 0-2ZM15 20a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

.ie_ydxblm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 15v3a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-3c0-.17-.141-.401-.225-.542q-.195-.325-.786-1.102C6.013 12.076 5 10.686 5 9a7 7 0 1 1 14 0c0 1.686-1.013 3.076-1.989 4.356q-.591.777-.786 1.102c-.084.141-.225.372-.225.542");
}

</style>
