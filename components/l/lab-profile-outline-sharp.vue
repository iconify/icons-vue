<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dru3q-jer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lab-profile-outline-sharp" /></template>
<style>
.dru3q-jer {
  fill: currentColor;
  d: path("M8.5 11.5v-1h7v1zm0-4v-1h7v1zm-2.5 7h8.725L18 18.758V4H6zM6 20h11.685l-3.435-4.5H6zm13 1H5V3h14zM6 20V4zm0-4.5v-1z");
}

</style>
