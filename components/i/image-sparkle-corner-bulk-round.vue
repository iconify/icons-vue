<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xn4n-1bjv"/><path class="ojffzi6ed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-sparkle-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ojffzi6ed {
  d: path("M13.158 7.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m-6.865 5.072A3.82 3.82 0 0 1 9 11.171a3.82 3.82 0 0 1 2.707 1.122a.999.999 0 1 1-1.414 1.414a1.83 1.83 0 0 0-2.586 0l-4 4a.999.999 0 1 1-1.414-1.414Zm8.696 4.706c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375l.001-.003a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177l.003.001a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375l-.001.003a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L14.986 19a1 1 0 0 1 0-2Z");
}

.xn4n-1bjv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 12h-6c-.796 0-1.559.316-2.121.879A3 3 0 0 0 12 15v6a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v4a1 1 0 0 1-1 1");
}

</style>
