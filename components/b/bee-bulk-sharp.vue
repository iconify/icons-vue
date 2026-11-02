<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p4z9am1vm"/><path class="wsws-sbhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bee-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p4z9am1vm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 11h6c1.553 0 2.974.499 4.187 1.469c1.029.823 1.828 1.884 2.613 2.931a1 1 0 0 1 0 1.2c-.785 1.047-1.584 2.108-2.613 2.931A6.58 6.58 0 0 1 14 21H8a5 5 0 0 1 0-10");
}

.wsws-sbhl {
  d: path("M9 12c0-2.166.348-4.552 1.531-6.412c.489-.767 1.128-1.438 1.914-1.902A5 5 0 0 1 15 3c1.348 0 2.866.548 3.615 1.731c.241.38.385.816.385 1.269c0 .796-.301 1.522-.796 2.137c-.414.512-.929.93-1.438 1.342c-.602.487-1.362 1.066-1.643 1.814A2 2 0 0 0 15 12v8a1 1 0 0 1-2 0v-8c0-1.418.684-2.473 1.69-3.387c.264-.24.541-.464.817-.688c.398-.322.817-.643 1.14-1.044C16.849 6.63 17 6.328 17 6a.4.4 0 0 0-.075-.199a1.3 1.3 0 0 0-.36-.356C16.114 5.13 15.544 5 15 5c-1.234.001-2.135.646-2.781 1.662C11.258 8.173 11 10.247 11 12v8a1 1 0 0 1-2 0Zm-1.99 3a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

</style>
