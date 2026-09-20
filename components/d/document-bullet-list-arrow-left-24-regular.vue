<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4tmc-b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-bullet-list-arrow-left-24-regular" /></template>
<style>
.o4tmc-b7y {
  fill: currentColor;
  d: path("M10.75 11.5a.75.75 0 0 0-.72.54c.423.275.813.598 1.16.96h5.06a.75.75 0 0 0 0-1.5zM5.5 4v7.076a6.5 6.5 0 0 0-1.5.422V4a2 2 0 0 1 2-2h6.172c.515 0 1.047.22 1.413.586l5.829 5.828A2 2 0 0 1 20 9.828V20a2 2 0 0 1-2 2h-6.81a6.5 6.5 0 0 0 1.078-1.5H18a.5.5 0 0 0 .5-.5V10H14a2 2 0 0 1-2-2V3.5H6a.5.5 0 0 0-.5.5m10.75 15h-3.424A6.5 6.5 0 0 0 13 17.5h3.25a.75.75 0 0 1 0 1.5m0-3h-3.424a6.5 6.5 0 0 0-.558-1.5h3.982a.75.75 0 0 1 0 1.5M13.5 4.621V8a.5.5 0 0 0 .5.5h3.378zM6.5 23a5.5 5.5 0 1 1 0-11a5.5 5.5 0 0 1 0 11m3-5a.5.5 0 0 0 0-1H4.707l1.647-1.646a.5.5 0 0 0-.708-.708l-2.5 2.5a.5.5 0 0 0 0 .708l2.5 2.5a.5.5 0 0 0 .708-.708L4.707 18z");
}

</style>
