<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y36f8sbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:insert-page-break-sharp" /></template>
<style>
.y36f8sbpt {
  fill: currentColor;
  d: path("M5 21v-4.5h14V21zm9-13h4l-4-4zm-4.808 6.5v-1h5.616v1zm7.616 0v-1h5.615v1zm-15.231 0v-1h5.615v1zM5 11.5V3h9.5L19 7.5v4z");
}

</style>
