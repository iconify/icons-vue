<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rggm4bclc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-help-fill-sharp" /></template>
<style>
.rggm4bclc {
  fill: currentColor;
  d: path("M2.954 16.131A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046l-4.673.935a1 1 0 0 1-1.177-1.177Zm6.282-6.299A3 3 0 0 0 9 11a1 1 0 0 0 2 0a1.001 1.001 0 0 1 1.707-.707a1 1 0 0 1 .215 1.094A.99.99 0 0 1 12 12a1 1 0 0 0 0 2a3 3 0 1 0-2.764-4.168M12.01 15H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
