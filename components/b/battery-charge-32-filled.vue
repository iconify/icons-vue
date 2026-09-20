<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i3iry6x8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-charge-32-filled" /></template>
<style>
.i3iry6x8b {
  fill: currentColor;
  d: path("M10.157 9.754c-.624 1.259.286 2.744 1.698 2.746h.647v3.005l.008.194c.168 1.958 2.87 2.527 3.782.696l3.554-7.145v-.001C20.053 8.836 20.09 8.4 20 8h3.5a4.5 4.5 0 0 1 4.5 4.5v.5h.5a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5H28v.5a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 2 19.5v-7A4.5 4.5 0 0 1 6.5 8h4.53zm4.896-6.478c.235-.473.948-.305.948.223v4.505h2.143a.4.4 0 0 1 .359.578l-3.554 7.145c-.235.473-.947.306-.947-.222v-4.506h-2.145a.4.4 0 0 1-.357-.577z");
}

</style>
