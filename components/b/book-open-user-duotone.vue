<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="dzn3unt1c"/><path class="jzjoyosyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:book-open-user-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dzn3unt1c {
  d: path("M232 80v120h-72a32 32 0 0 0-32 32a32 32 0 0 0-32-32H24V80h72a32 32 0 0 1 32 32a32 32 0 0 1 32-32Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jzjoyosyu {
  d: path("M232 72h-72a40 40 0 0 0-32 16a40 40 0 0 0-32-16H24a8 8 0 0 0-8 8v120a8 8 0 0 0 8 8h72a24 24 0 0 1 24 24a8 8 0 0 0 16 0a24 24 0 0 1 24-24h72a8 8 0 0 0 8-8V80a8 8 0 0 0-8-8M96 192H32V88h64a24 24 0 0 1 24 24v88a39.8 39.8 0 0 0-24-8m128 0h-64a39.8 39.8 0 0 0-24 8v-88a24 24 0 0 1 24-24h64ZM89.6 43.19a48 48 0 0 1 76.8 0a8 8 0 0 1-12.79 9.62a32 32 0 0 0-51.22 0a8 8 0 1 1-12.79-9.62");
}

</style>
