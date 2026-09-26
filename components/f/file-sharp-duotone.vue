<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n8-gi9vyb"/><path clip-rule="evenodd" class="rceiv1tin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n8-gi9vyb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 1C14.2652 1 14.5196 1.1054 14.7071 1.2929L20.7071 7.2929C20.8946 7.4804 21 7.7348 21 8L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 2C3 1.4477 3.4477 1 4 1L14 1Z");
}

.rceiv1tin {
  fill-rule: evenodd;
  d: path("M13 1L14.4142 1L21 7.5858L21 9L13 9ZM15 4.4142L15 7L17.5858 7Z");
}

</style>
