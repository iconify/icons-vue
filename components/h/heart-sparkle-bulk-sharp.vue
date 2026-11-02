<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ox1bc9gwd"/><path class="yswm6vqbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-sparkle-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ox1bc9gwd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 5.247a6.24 6.24 0 0 1 3.552-1.939c2.656-.469 5.187.78 6.089 3.393c.254.738.359 1.52.359 2.299c-.001 1.72-.645 3.359-1.565 4.791c-.895 1.391-2.038 2.61-3.271 3.706a29 29 0 0 1-3.203 2.46c-.482.321-.969.636-1.475.917a1 1 0 0 1-.972 0a22 22 0 0 1-1.475-.917a29 29 0 0 1-3.203-2.46c-1.233-1.096-2.376-2.315-3.271-3.706C2.645 12.359 2.001 10.72 2 9c0-.779.105-1.561.359-2.299c.902-2.613 3.433-3.862 6.089-3.393A6.24 6.24 0 0 1 12 5.247");
}

.yswm6vqbi {
  d: path("m8.986 12l.003-.001c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375L11 9.986a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177l.003.001a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375l-.001.003a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L8.986 14a1 1 0 0 1 0-2");
}

</style>
