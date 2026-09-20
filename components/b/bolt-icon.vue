<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":326};
const content = `<path class="m6v8a0bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:bolt-icon" /></template>
<style>
.m6v8a0bep {
  d: path("m146.913 0l-21.902 98.78c17.69-19.335 34.117-26.481 55.175-26.481c45.49 0 75.814 29.844 75.814 84.489c0 56.325-34.958 128.625-107.402 128.625c-23.166 0-45.91-8.407-58.966-26.481l-4.606 21.316L0 325.328l9.179-45.08L71.099 0zm-2.948 139.134c-11.794 0-21.902 5.043-30.747 13.872l-11.793 51.7c8.002 8.828 20.217 13.873 33.695 13.873c24.008 0 42.54-19.757 42.54-45.817c0-20.177-15.584-33.628-33.695-33.628");
}

</style>
