<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ldp73_bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-agenda-clock-28-regular" /></template>
<style>
.ldp73_bcg {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m1.25-11A3.25 3.25 0 0 1 25 6.25v8.25a7.5 7.5 0 0 0-1.5-.874V6.25a1.75 1.75 0 0 0-1.75-1.75H6.25A1.75 1.75 0 0 0 4.5 6.25v15.5c0 .966.784 1.75 1.75 1.75h7.376A7.5 7.5 0 0 0 14.5 25H6.25A3.25 3.25 0 0 1 3 21.75V6.25A3.25 3.25 0 0 1 6.25 3zM20.5 16.5a.5.5 0 0 0-.5.5v3.5a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 0-1H21v-3a.5.5 0 0 0-.5-.5m-7.228 2a7.5 7.5 0 0 0-.253 1.5H9a.75.75 0 0 1-.102-1.493L9 18.5zm5.305-5.25a7.5 7.5 0 0 0-2.89 1.5H9a.75.75 0 0 1-.102-1.493L9 13.25zM19 8a.75.75 0 0 1 .102 1.493L19 9.5H9a.75.75 0 0 1-.102-1.493L9 8z");
}

</style>
