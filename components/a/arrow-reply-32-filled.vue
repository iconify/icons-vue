<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a7fxeabzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reply-32-filled" /></template>
<style>
.a7fxeabzq {
  fill: currentColor;
  d: path("M12.134 6.366a1.25 1.25 0 0 1 0 1.768L7.268 13h9.482C23.515 13 29 18.485 29 25.25v.5a1.25 1.25 0 1 1-2.5 0v-.5a9.75 9.75 0 0 0-9.75-9.75H7.268l4.866 4.866a1.25 1.25 0 0 1-1.768 1.768l-7-7a1.25 1.25 0 0 1 0-1.768l7-7a1.25 1.25 0 0 1 1.768 0");
}

</style>
