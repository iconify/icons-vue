<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p8ofxc8sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-open-48-regular" /></template>
<style>
.p8ofxc8sp {
  fill: currentColor;
  d: path("M37 4a9 9 0 0 1 9 9v1.75a1.25 1.25 0 1 1-2.5 0V13a6.5 6.5 0 1 0-13 0v5h2.25A6.25 6.25 0 0 1 39 24.25v13.5A6.25 6.25 0 0 1 32.75 44h-17.5A6.25 6.25 0 0 1 9 37.75v-13.5A6.25 6.25 0 0 1 15.25 18H28v-5a9 9 0 0 1 9-9M15.25 20.5a3.75 3.75 0 0 0-3.75 3.75v13.5a3.75 3.75 0 0 0 3.75 3.75h17.5a3.75 3.75 0 0 0 3.75-3.75v-13.5a3.75 3.75 0 0 0-3.75-3.75zm8.75 8a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5");
}

</style>
