<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="rbno8frrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-agenda-clock-28-filled" /></template>
<style>
.rbno8frrk {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m1.25-11A3.25 3.25 0 0 1 25 6.25v8.25a7.5 7.5 0 0 0-6.423-1.25H9l-.102.007a.75.75 0 0 0 0 1.486L9 14.75h6.687a7.5 7.5 0 0 0-2.415 3.75H9l-.102.007a.75.75 0 0 0 0 1.486L9 20h4.019a7.47 7.47 0 0 0 1.481 5H6.25A3.25 3.25 0 0 1 3 21.75V6.25A3.25 3.25 0 0 1 6.25 3zM20.5 16.5a.5.5 0 0 0-.5.5v3.5a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 0-1H21v-3a.5.5 0 0 0-.5-.5M8.898 8.007a.75.75 0 0 0 0 1.486L9 9.5h10l.102-.007a.75.75 0 0 0 0-1.486L19 8H9z");
}

</style>
