<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="awtf63llh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:channel-arrow-right-20-filled" /></template>
<style>
.awtf63llh {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0-7A2.5 2.5 0 0 1 17 5.5v4.1c-.75-.383-1.6-.6-2.5-.6a5.49 5.49 0 0 0-4.242 2H7.5a.5.5 0 0 0 0 1h2.102C9.218 12.75 9 13.6 9 14.5s.218 1.75.602 2.5H5.5A2.5 2.5 0 0 1 3 14.5V8.437q.24.061.5.063a2 2 0 1 0-.302-3.978A2.5 2.5 0 0 1 5.5 3zm.354 9.147a.5.5 0 1 0-.707.707L15.293 14H12.5a.5.5 0 0 0 0 1h2.793l-1.146 1.146a.5.5 0 1 0 .707.707l2.002-2.001a.503.503 0 0 0-.003-.706zM7.5 8a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zm-4-2.5a1 1 0 1 1 0 2a1 1 0 0 1 0-2");
}

</style>
