<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4cjto2mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:30fps-sharp" /></template>
<style>
.j4cjto2mi {
  fill: currentColor;
  d: path("M2.885 18.116v-1.231h6v-4.27h-6v-1.23h6v-4.27h-6v-1.23h7.23v5.5L9.5 12l.616.616v5.5zm11.23-1.231h5.77v-9.77h-5.77zm-1.23 1.23V5.886h8.23v12.23z");
}

</style>
