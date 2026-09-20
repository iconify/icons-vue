<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je9v92b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:delete-sweep-sharp" /></template>
<style>
.je9v92b3t {
  fill: currentColor;
  d: path("M14.885 17.5v-1h3v1zm0-8v-1h6v1zm0 4v-1h5v1zM4.115 8h-1V7h3.731v-.885h2.538V7h3.732v1h-1v10h-8z");
}

</style>
