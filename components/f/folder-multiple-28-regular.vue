<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="zadlcnb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-multiple-28-regular" /></template>
<style>
.zadlcnb_w {
  fill: currentColor;
  d: path("M24.474 9.23a3.74 3.74 0 0 1 1.528 3.02v5.5a6.25 6.25 0 0 1-6.25 6.25h-11.5a3.74 3.74 0 0 1-3.022-1.53q.258.03.523.03h14a4.75 4.75 0 0 0 4.75-4.75v-8q0-.264-.03-.52M8.172 3c.73 0 1.429.29 1.944.806L12.31 6h7.444a3.75 3.75 0 0 1 3.75 3.75v8a3.75 3.75 0 0 1-3.75 3.75h-14a3.75 3.75 0 0 1-3.75-3.75v-11A3.75 3.75 0 0 1 5.754 3zm1.944 6.694a2.75 2.75 0 0 1-1.944.806H3.504v7.25A2.25 2.25 0 0 0 5.754 20h14a2.25 2.25 0 0 0 2.25-2.25v-8a2.25 2.25 0 0 0-2.25-2.25H12.31zM5.754 4.5a2.25 2.25 0 0 0-2.25 2.25V9h4.668c.331 0 .65-.132.884-.366L10.94 6.75L9.056 4.866a1.25 1.25 0 0 0-.884-.366z");
}

</style>
