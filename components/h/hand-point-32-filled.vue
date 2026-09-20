<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a5_q7-b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hand-point-32-filled" /></template>
<style>
.a5_q7-b9q {
  fill: currentColor;
  d: path("M12.004 5.5a3.5 3.5 0 0 1 3.5-3.5A3.496 3.496 0 0 1 19 5.5v5.545l4.06.621c4.085.627 6.741 4.634 5.726 8.639l-1.51 5.96a4 4 0 0 1-3.279 2.972l-4.731.718c-2.086.316-3.828-1.054-4.644-2.692c-1.131-2.271-3.827-5.337-11.706-8.72c-.849-.366-1.202-1.44-.642-2.238a6.92 6.92 0 0 1 8.356-2.394l1.374.58z");
}

</style>
