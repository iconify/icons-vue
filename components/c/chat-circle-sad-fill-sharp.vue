<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9e-w_b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-sad-fill-sharp" /></template>
<style>
.l9e-w_b3n {
  fill: currentColor;
  d: path("M2.954 16.131A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046l-4.673.935a1 1 0 0 1-1.177-1.177ZM9 8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm6 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-5.504 4.831a6.6 6.6 0 0 0-2.203 1.462a.999.999 0 1 0 1.414 1.414A4.64 4.64 0 0 1 12 14.343a4.64 4.64 0 0 1 3.293 1.364a.999.999 0 1 0 1.414-1.414a6.6 6.6 0 0 0-2.203-1.462A6.6 6.6 0 0 0 12 12.343a6.6 6.6 0 0 0-2.504.488");
}

</style>
