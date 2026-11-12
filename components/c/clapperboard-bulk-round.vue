<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c2a762byt"/><path class="d9kouh5ef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clapperboard-bulk-round" /></template>
<style>
.c2a762byt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m2.58 9.184l-.379-2.017a2 2 0 0 1 1.598-2.334l14.034-2.632a2 2 0 0 1 2.334 1.598l.194 1.034a2 2 0 0 1-1.597 2.334L14.322 8H17a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5v-4c0-1.135.381-2.232 1.091-3.118a1 1 0 0 1-.511-.698");
}

.cuyn6tgcc {
  fill: currentColor;
}

.d9kouh5ef {
  d: path("m2.58 9.184l-.379-2.017a2 2 0 0 1 1.598-2.334l14.034-2.632a2 2 0 0 1 2.334 1.598l.194 1.034a2 2 0 0 1-1.597 2.334L3.747 9.983a1 1 0 0 1-1.167-.799m15.815-3.983l-.194-1.034l-3.367.632l.194 1.034ZM9.5 5.799l.194 1.034l3.368-.632l-.194-1.034Zm-5.333 1l.194 1.034l3.368-.632l-.194-1.034ZM9 12.5a1.284 1.284 0 0 1 1.943-1.1l4.143 2.485a1.3 1.3 0 0 1 0 2.23L10.943 18.6A1.284 1.284 0 0 1 9 17.5Z");
}

</style>
