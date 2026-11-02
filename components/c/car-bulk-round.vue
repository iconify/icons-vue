<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ejuy_kbus"/><path class="y2_vcqbcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ejuy_kbus {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 16v-6c0-.155.036-.308.106-.447l2-4C5.848 4.069 7.307 3 9 3h6c1.693 0 3.152 1.069 3.894 2.553l2 4c.07.139.106.292.106.447v6c0 1.27-.803 2.405-2 2.829V20a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1H9v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1.171A3 3 0 0 1 3 16m15.382-7l-1.171-2.342l-.002-.004A3 3 0 0 0 14.528 5H9.472a3 3 0 0 0-2.681 1.654L5.618 9Z");
}

.y2_vcqbcb {
  d: path("M3 11a1 1 0 0 1 0-2h.382l1.724-3.447C5.848 4.069 7.307 3 9 3h6c1.693 0 3.152 1.069 3.894 2.553L20.618 9H21a1 1 0 0 1 0 2Zm15.382-2l-1.276-2.553C16.706 5.649 15.926 5 15 5H9c-.926 0-1.706.649-2.106 1.447L5.618 9ZM8 13h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m8 0h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2");
}

</style>
