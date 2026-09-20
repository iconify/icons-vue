<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kyd-blg6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-charge-32-regular" /></template>
<style>
.kyd-blg6e {
  fill: currentColor;
  d: path("M10.157 9.754q-.06.12-.1.246H6.5A2.5 2.5 0 0 0 4 12.5v7A2.5 2.5 0 0 0 6.5 22h17a2.5 2.5 0 0 0 2.5-2.5v-7a2.5 2.5 0 0 0-2.5-2.5h-4.027l.373-.75v-.001c.206-.413.243-.85.154-1.25h3.5a4.5 4.5 0 0 1 4.5 4.5v.5h.5a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5H28v.5a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 2 19.5v-7A4.5 4.5 0 0 1 6.5 8h4.53zm4.896-6.479c.235-.472.946-.305.947.223v4.506h2.145a.4.4 0 0 1 .358.578l-3.554 7.144c-.235.473-.947.306-.947-.222V11h-2.145a.4.4 0 0 1-.358-.578z");
}

</style>
