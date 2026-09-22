<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjvwrs0gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-plus-sharp" /></template>
<style>
.bjvwrs0gm {
  fill: currentColor;
  d: path("M8.5 19v-6.346L2.45 5h14.1l-6.05 7.654V19zm8.539 0v-2.962h-2.981v-1h2.98v-2.98h1v2.98H21v1h-2.962V19z");
}

</style>
