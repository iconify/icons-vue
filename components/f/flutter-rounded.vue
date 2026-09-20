<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-_f716sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flutter-rounded" /></template>
<style>
.d-_f716sf {
  fill: currentColor;
  d: path("M6.746 14.856L3.866 12l9.307-9.308h5.737zm6.427 6.452l-5.021-5.021l5.021-5.002h5.737l-5.021 5.002l5.02 5.02z");
}

</style>
