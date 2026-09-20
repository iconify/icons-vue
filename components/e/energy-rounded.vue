<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjeaqyb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:energy-rounded" /></template>
<style>
.gjeaqyb-p {
  fill: currentColor;
  d: path("M9 22v-1q0-.8.6-1.338T11 19v-7.15q-.55-.2-.962-.575T9.35 10.4l-1.9.5q-.9.2-1.713-.15T4.7 9.55l4.35-1.1q.2-1.025.95-1.7T11.8 6l.6-2.25q.25-.875.963-1.387t1.587-.313l-1.25 4.5q.625.4.963 1.05T15 9q0 .325-.075.638t-.175.612l1.35 1.4q.625.65.738 1.525t-.488 1.475l-3-3q-.075.075-.162.113T13 11.85V19q.8.125 1.4.663T15 21v1zm4.063-11.937Q13.5 9.625 13.5 9t-.437-1.062T12 7.5t-1.062.438T10.5 9t.438 1.063T12 10.5t1.063-.437");
}

</style>
