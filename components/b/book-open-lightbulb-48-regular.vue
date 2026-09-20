<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="elb2nupgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-lightbulb-48-regular" /></template>
<style>
.elb2nupgy {
  fill: currentColor;
  d: path("M40.402 41.99A2.5 2.5 0 0 1 37.95 44h-1.9a2.5 2.5 0 0 1-2.452-2.01L33.199 40h7.6zM20 8c1.602 0 3.037.718 4 1.85A5.24 5.24 0 0 1 28 8h13.25A2.75 2.75 0 0 1 44 10.75v12.11a10 10 0 0 0-2.5-1.79V10.75a.25.25 0 0 0-.25-.25H28a2.75 2.75 0 0 0-2.75 2.75v21.5A2.75 2.75 0 0 0 28 37.5h2.39q.16.142.326.277L31.16 40H28a5.24 5.24 0 0 1-4-1.85A5.24 5.24 0 0 1 20 40H6.75A2.75 2.75 0 0 1 4 37.25v-26.5A2.75 2.75 0 0 1 6.75 8zm17 14a8 8 0 0 1 4.473 14.633L41.199 38h-8.4l-.273-1.367A8 8 0 0 1 37 22M6.75 10.5a.25.25 0 0 0-.25.25v26.5c0 .138.112.25.25.25H20a2.75 2.75 0 0 0 2.75-2.75v-21.5A2.75 2.75 0 0 0 20 10.5z");
}

</style>
