<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uld6wngev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grading-sharp" /></template>
<style>
.uld6wngev {
  fill: currentColor;
  d: path("m15.964 19.994l-2.133-2.132l.688-.689l1.425 1.425l3.348-3.348l.708.708zM4 20v-1h8v1zm0-3.75v-1h8v1zm0-3.75v-1h16v1zm0-3.75v-1h16v1zM4 5V4h16v1z");
}

</style>
