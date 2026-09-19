<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8-_i_47b"/><path class="ijfk2hwes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-warning-amber" /></template>
<style>
.g8-_i_47b {
  fill: currentColor;
  d: path("M12 5.99L19.53 19H4.47zM12 2L1 21h22z");
}

.ijfk2hwes {
  fill: currentColor;
  d: path("M13 16h-2v2h2zm0-6h-2v5h2z");
}

</style>
