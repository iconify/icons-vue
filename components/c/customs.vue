<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r9rioofmx"/><path class="zg8y7ib2g"/><path class="u4s-m_n8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:customs" /></template>
<style>
.r9rioofmx {
  fill: var(--svg-color--269, #269);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.u4s-m_n8j {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M15 28H6v-9a2 2 0 0 0-4 0v9a2 2 0 0 0 2 2a2 2 0 0 0 2 2h9a2 2 0 0 0 0-4");
}

.zg8y7ib2g {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M32.828 9a6 6 0 0 1-12 0zm0-6h-12a1 1 0 0 0-1 1c0 .182.049.569.134 1.007c-.045-.002-.088-.007-.134-.007c-1.104 0-2 .448-2 1s.896 1 2 1c.37 0 .684-.003.971-.008c.01.002.019.008.029.008h12c.553 0 1-2.448 1-3s-.447-1-1-1m-.18 15.18L20.828 30a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V19c0-.293-.066-.569-.18-.82M29.828 17h-7c-.057 0-.11.012-.166.017c-1.318-.07-2.796.118-3.248.569l-5.828 6a2 2 0 0 0 2.829 2.829l4.413-4.544V26z");
}

</style>
