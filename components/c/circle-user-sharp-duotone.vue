<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l5jfifdpj"/><path clip-rule="evenodd" class="dw8_9rjae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-user-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dw8_9rjae {
  fill-rule: evenodd;
  d: path("M12 6C13.519 6 15 7.481 15 9C15 10.519 13.519 12 12 12C10.481 12 9 10.519 9 9C9 7.481 10.481 6 12 6ZM11 14H13C15.665 14 17.842 16.086 18 18.708C16.35 20.184 14.214 21 12 21C9.786 21 7.65 20.184 6 18.708C6.157 16.086 8.335 14 11 14Z");
}

.l5jfifdpj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C17.937 1 23 6.063 23 12C23 17.937 17.937 23 12 23C6.063 23 1 17.937 1 12C1 6.063 6.063 1 12 1Z");
}

</style>
