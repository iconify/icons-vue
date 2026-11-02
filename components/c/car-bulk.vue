<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q5n7lbbeo"/><path class="yusie0bco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q5n7lbbeo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 19v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1.171A3 3 0 0 1 3 16v-6c0-.155.036-.308.106-.447l2-4C5.643 4.478 6.652 3.001 8 3h8c1.348.001 2.357 1.478 2.894 2.553l2 4c.07.139.106.292.106.447v6c0 1.27-.803 2.405-2 2.829V20a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1Zm9.382-10l-1.724-3.447A1 1 0 0 0 15.764 5H8.236a1 1 0 0 0-.894.553L5.618 9Z");
}

.yusie0bco {
  d: path("M3 11a1 1 0 0 1 0-2h.382l1.724-3.447C5.643 4.478 6.652 3.001 8 3h8c1.348.001 2.357 1.478 2.894 2.553L20.618 9H21a1 1 0 0 1 0 2Zm15.382-2l-1.276-2.553c-.216-.431-.47-.857-.813-1.2c-.093-.093-.2-.197-.324-.247H8.031c-.124.05-.231.154-.324.247c-.343.343-.597.769-.813 1.2L5.618 9ZM8 13h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m8 0h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2");
}

</style>
