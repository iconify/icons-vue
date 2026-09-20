<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9x_5qbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-arrow-down-off-24-regular" /></template>
<style>
.y9x_5qbhg {
  fill: currentColor;
  d: path("M6.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-.92-.919A2 2 0 0 1 18 22h-6.81a6.5 6.5 0 0 0 1.078-1.5H18a.5.5 0 0 0 .5-.5v-.44l-13-13v4.516a6.5 6.5 0 0 0-1.5.422V5.061L2.22 3.28a.75.75 0 0 1 0-1.061M6.5 14a.5.5 0 0 0-.5.5v4.793l-1.646-1.646a.5.5 0 1 0-.708.707l2.5 2.5a.5.5 0 0 0 .708 0l2.5-2.5a.5.5 0 1 0-.708-.707L7 19.293V14.5a.5.5 0 0 0-.5-.5m5.672-12c.53 0 1.04.21 1.415.586l5.827 5.827c.375.375.586.885.586 1.415v6.99l-1.5-1.5V10H14a2 2 0 0 1-2-2V3.5H6.682L5.307 2.125A2 2 0 0 1 6 2zM13.5 8a.5.5 0 0 0 .5.5h3.379L13.5 4.621z");
}

</style>
