<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6ab3756g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-wink-fill-round" /></template>
<style>
.z6ab3756g {
  fill: currentColor;
  d: path("M2.954 16.131A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046l-4.673.935a1 1 0 0 1-1.177-1.177ZM9 8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm5 0a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2Zm-3.753 6.316a4.6 4.6 0 0 1-1.54-1.023a.999.999 0 1 0-1.414 1.414a6.6 6.6 0 0 0 2.203 1.462c.795.324 1.645.49 2.504.488a6.6 6.6 0 0 0 2.504-.488a6.6 6.6 0 0 0 2.203-1.462a.997.997 0 0 0 0-1.414a1 1 0 0 0-1.414 0a4.65 4.65 0 0 1-5.046 1.023");
}

</style>
