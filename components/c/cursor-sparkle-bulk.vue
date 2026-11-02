<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fzd5ie_fo"/><path class="whhvmkbqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-sparkle-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fzd5ie_fo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.316 11.051l9 3a1 1 0 0 1 0 1.898l-1.473.491a2.416 2.416 0 0 1-3.403 3.403l-.491 1.473a1 1 0 0 1-1.898 0l-3-9a1.001 1.001 0 0 1 1.265-1.265");
}

.whhvmkbqa {
  d: path("M2 7a1 1 0 0 1 1-1c.363 0 .718-.097 1.046-.25c.371-.175.709-.415.997-.707c.292-.288.532-.626.707-.997C5.903 3.718 6 3.363 6 3a1 1 0 0 1 2 0c0 .363.097.718.25 1.046c.175.371.415.709.707.997c.288.292.626.532.997.707c.328.153.683.25 1.046.25a1 1 0 0 1 0 2c-.363 0-.718.097-1.046.25a3.5 3.5 0 0 0-.997.707a3.5 3.5 0 0 0-.707.997C8.097 10.282 8 10.637 8 11a1 1 0 0 1-2 0c0-.363-.097-.718-.25-1.046a3.5 3.5 0 0 0-.707-.997a3.5 3.5 0 0 0-.997-.707A2.5 2.5 0 0 0 3 8a1 1 0 0 1-1-1");
}

</style>
