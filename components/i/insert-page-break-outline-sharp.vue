<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6nbq32rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:insert-page-break-outline-sharp" /></template>
<style>
.v6nbq32rb {
  fill: currentColor;
  d: path("M5 21v-4.5h1V20h12v-3.5h1V21zm0-9.5V3h9.5L19 7.5v4h-1V8h-4V4H6v7.5zm4.192 3v-1h5.616v1zm7.616 0v-1h5.615v1zm-15.231 0v-1h5.615v1zM12 16.5");
}

</style>
