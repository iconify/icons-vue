<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ludw9ihxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-word-24-regular" /></template>
<style>
.ludw9ihxy {
  fill: currentColor;
  d: path("M10 11a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2zm2.172-9c.53 0 1.04.21 1.415.586l5.827 5.827c.375.375.586.885.586 1.415V20a2 2 0 0 1-2 2h-5.769c.371-.413.631-.928.727-1.5H18a.5.5 0 0 0 .5-.5V10H14a2 2 0 0 1-2-2V3.5H6a.5.5 0 0 0-.5.5v6H4V4a2 2 0 0 1 2-2zM8.808 13.501L8.06 17.46l-.797-3.959H5.7l-.76 3.959l-.767-3.959H2.9L4.142 19.5h1.56l.798-3.6l.763 3.6l1.545-.001L10.1 13.5zM13.5 8a.5.5 0 0 0 .5.5h3.379L13.5 4.621z");
}

</style>
