<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvcw17b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-arrow-down-off-24-filled" /></template>
<style>
.xvcw17b-h {
  fill: currentColor;
  d: path("M6.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-.92-.919A2 2 0 0 1 18 22h-6.81A6.5 6.5 0 0 0 4 11.498V5.061L2.22 3.28a.75.75 0 0 1 0-1.061M6.5 14a.5.5 0 0 0-.5.5v4.793l-1.646-1.646a.5.5 0 1 0-.708.707l2.5 2.5a.5.5 0 0 0 .708 0l2.5-2.5a.5.5 0 1 0-.708-.707L7 19.293V14.5a.5.5 0 0 0-.5-.5m6.194-4.487c.35.303.806.487 1.306.487h6v6.818zM12 8c0 .5.184.954.486 1.305l-7.18-7.18C5.524 2.045 5.757 2 6 2h6zm7.5.5H14a.5.5 0 0 1-.5-.5V2.5z");
}

</style>
