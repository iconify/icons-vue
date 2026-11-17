<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dl-9g0b0v"/><path class="ye4y7zacs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-play-half-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dl-9g0b0v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 8a1 1 0 0 1 1.555-.832l6 4a1 1 0 0 1 0 1.664l-6 4A1 1 0 0 1 9 16Z");
}

.ye4y7zacs {
  d: path("M9.68 2.701a1 1 0 0 1 .756-.578c.68-.107 1.371-.145 2.059-.111a10.002 10.002 0 0 1 .827 19.902c-.959.127-1.931.113-2.886-.037a1 1 0 0 1 .313-1.976a8 8 0 0 0 6.908-2.244a8 8 0 0 0-6.908-13.558A1.002 1.002 0 0 1 9.68 2.701M7.616 4.295v.001a1 1 0 0 1-.318 1.232a8 8 0 0 0-1.77 1.77A1 1 0 0 1 3.91 6.122A10 10 0 0 1 6.122 3.91a1 1 0 0 1 1.494.385M9 8a1 1 0 0 1 1.555-.832l6 4a1 1 0 0 1 0 1.664l-6 4A1 1 0 0 1 9 16Zm-6.301 6.319a1 1 0 0 1-.576-.755a10 10 0 0 1 0-3.128a1.004 1.004 0 0 1 1.145-.832c.545.087.917.599.831 1.145a7.9 7.9 0 0 0 0 2.502a1 1 0 0 1-1.4 1.068M11 14.131L14.197 12L11 9.869Zm-6.701 2.252c.434-.2.948-.066 1.229.32a8 8 0 0 0 1.77 1.77a1 1 0 0 1-1.176 1.618a10 10 0 0 1-2.212-2.212a1 1 0 0 1 .389-1.495");
}

</style>
