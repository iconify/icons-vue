<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j61d6ybyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-squint-sharp-fill" /></template>
<style>
.j61d6ybyv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.778 4.222C21.768 6.211 23 8.963 23 12C23 18.075 18.075 23 12 23C5.925 23 1 18.075 1 12C1 5.925 5.925 1 12 1C15.037 1 17.789 2.232 19.778 4.222ZM8.78 6.432L7.5 7.969L7.86 8.268L8.438 8.75L7.86 9.232L7.5 9.531L8.78 11.068L9.14 10.768L10.64 9.518C10.868 9.328 11 9.047 11 8.75C11 8.453 10.868 8.172 10.64 7.982L9.14 6.732L8.78 6.432ZM16.5 7.969L15.22 6.432L14.86 6.732L13.36 7.982C13.132 8.172 13 8.453 13 8.75C13 9.047 13.132 9.328 13.36 9.518L14.86 10.768L15.22 11.068L16.5 9.531L16.14 9.232L15.562 8.75L16.14 8.268L16.5 7.969ZM12 13H8C7.448 13 7 13.448 7 14C7 16.761 9.239 19 12 19C14.761 19 17 16.761 17 14C17 13.448 16.552 13 16 13H12Z");
}

</style>
