<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="x2_qh3rzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-multiple-28-filled" /></template>
<style>
.x2_qh3rzs {
  fill: currentColor;
  d: path("M24.474 9.23a3.74 3.74 0 0 1 1.528 3.02v5.5a6.25 6.25 0 0 1-6.25 6.25h-11.5a3.74 3.74 0 0 1-3.022-1.53q.258.03.523.03h14a4.75 4.75 0 0 0 4.75-4.75v-8q0-.264-.03-.52M19.754 6a3.75 3.75 0 0 1 3.75 3.75v8a3.75 3.75 0 0 1-3.75 3.75h-14a3.75 3.75 0 0 1-3.75-3.75V10.5h6.168c.73 0 1.429-.29 1.944-.806L13.81 6zM8.172 3c.73 0 1.429.29 1.944.806L12 5.689L9.056 8.634A1.25 1.25 0 0 1 8.172 9H2.004V6.75A3.75 3.75 0 0 1 5.754 3z");
}

</style>
