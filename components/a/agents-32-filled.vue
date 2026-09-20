<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e-a1qjbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-32-filled" /></template>
<style>
.e-a1qjbru {
  fill: currentColor;
  d: path("M16.683 3a5.1 5.1 0 0 0-.903 1.827l-5.496 20.666a1 1 0 1 0 1.932.514l5.497-20.666a3.15 3.15 0 0 1 2.996-2.34A4 4 0 0 1 24.117 5l5.485 9.5a3 3 0 0 1 0 3l-5.773 10A3 3 0 0 1 21.23 29h-5.914c.41-.53.722-1.148.902-1.827l5.498-20.67a1 1 0 0 0-1.933-.513l-5.498 20.669a3.15 3.15 0 0 1-2.99 2.34A4 4 0 0 1 7.888 27l-5.485-9.5a3 3 0 0 1 0-3l5.773-10A3 3 0 0 1 10.773 3z");
}

</style>
