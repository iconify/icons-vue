<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="iipw5lbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-off-28-filled" /></template>
<style>
.iipw5lbus {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l22.5 22.5a.75.75 0 0 1-1.06 1.06L18.94 20H17a1 1 0 0 1-.116-1.993l.058-.004L13.94 15H8a1 1 0 0 1-.116-1.993L8 13h3.94l-3-3H8a4 4 0 0 0-.2 7.995L8 18h3a1 1 0 0 1 .116 1.993L11 20H8a6 6 0 0 1-.98-11.92l-4.8-4.8a.75.75 0 0 1 0-1.06M20 8a6 6 0 0 1 2.593 11.41l-1.55-1.549a4 4 0 0 0-.844-7.856L20 10h-3a1 1 0 0 1-.116-1.993L17 8zm0 5a1 1 0 0 1 .116 1.993L20 15h-1.817l-2-2z");
}

</style>
