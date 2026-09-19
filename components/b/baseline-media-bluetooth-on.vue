<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3f-0vuqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-media-bluetooth-on" /></template>
<style>
.b3f-0vuqm {
  fill: currentColor;
  d: path("m9 3l.01 10.55c-.6-.34-1.28-.55-2-.55a4.001 4.001 0 1 0 0 8C9.23 21 11 19.21 11 17V7h4V3zm12 9.43L17.57 9h-.6v4.55l-2.75-2.75l-.85.85L16.73 15l-3.35 3.35l.85.85l2.75-2.75V21h.6L21 17.57L18.42 15zm-2.83-1.13l1.13 1.13l-1.13 1.13zm1.13 6.27l-1.13 1.13v-2.26z");
}

</style>
