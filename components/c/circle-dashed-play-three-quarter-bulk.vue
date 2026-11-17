<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oljo26b2f"/><path class="bt0sm3cfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-play-three-quarter-bulk" /></template>
<style>
.bt0sm3cfy {
  d: path("M4 11.94A7.997 7.997 0 0 0 11.998 20H12a8.001 8.001 0 0 0 5.657-13.657a7.99 7.99 0 0 0-6.908-2.244a1 1 0 0 1-.313-1.976a10 10 0 0 1 11.542 9.215a10 10 0 0 1-8.656 10.576A10.004 10.004 0 0 1 2.123 10.436a1 1 0 0 1 1.976.313A8 8 0 0 0 4 11.94m3.616-7.645v.001a1 1 0 0 1-.318 1.232a8 8 0 0 0-1.77 1.77A1 1 0 0 1 3.91 6.122A10 10 0 0 1 6.122 3.91a1 1 0 0 1 1.494.385M9 9c0-.239.075-.47.216-.664c.257-.353.685-.508 1.112-.508c.39 0 .771.104 1.119.278l4 2a2.116 2.116 0 0 1 0 3.788l-4 2a2.5 2.5 0 0 1-1.119.278c-.427 0-.855-.155-1.112-.508A1.13 1.13 0 0 1 9 15Zm2 4.882l3.553-1.776a.12.12 0 0 0 .065-.106a.12.12 0 0 0-.065-.106L11 10.118Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.oljo26b2f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 9c0-.239.075-.47.216-.664c.257-.353.685-.508 1.112-.508c.39 0 .771.104 1.119.278l4 2a2.116 2.116 0 0 1 0 3.788l-4 2a2.5 2.5 0 0 1-1.119.278c-.427 0-.855-.155-1.112-.508A1.13 1.13 0 0 1 9 15Z");
}

</style>
