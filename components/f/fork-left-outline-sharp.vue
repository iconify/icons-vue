<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8lz3ioqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fork-left-outline-sharp" /></template>
<style>
.k8lz3ioqf {
  fill: currentColor;
  d: path("M13 21v-4q-.45-1.6-1.588-2.363t-2.487-.762q-.275 0-.55.038t-.55.087L9.4 15.6L8 17l-4-4l4-4l1.4 1.4L7.825 12q.225-.05.475-.075t.525-.025q1.1 0 2.2.338T13 13.35V6.825l-1.6 1.6L10 7l4-4l4 4l-1.4 1.4L15 6.825V21z");
}

</style>
