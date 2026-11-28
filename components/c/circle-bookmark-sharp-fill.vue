<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ktxm0rbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bookmark-sharp-fill" /></template>
<style>
.ktxm0rbyl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 12C23 18.075 18.075 23 12 23C5.925 23 1 18.075 1 12C1 5.925 5.925 1 12 1C18.075 1 23 5.925 23 12ZM16.747 11.984L16.731 7.298C16.729 6.747 16.282 6.301 15.731 6.301H8.269C7.718 6.301 7.271 6.747 7.269 7.298L7.236 16.669C7.236 17.225 7.684 17.673 8.236 17.673C8.368 17.673 8.499 17.647 8.621 17.596L12 16.19L15.379 17.596C15.501 17.647 15.632 17.673 15.764 17.673C16.316 17.673 16.764 17.225 16.764 16.673L16.747 11.984Z");
}

</style>
