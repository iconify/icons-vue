<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c751aybbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-hint-20-filled" /></template>
<style>
.c751aybbv {
  fill: currentColor;
  d: path("M2.5 13.5a.5.5 0 0 1 .5.5v.5A1.5 1.5 0 0 0 4.5 16H5a.5.5 0 0 1 0 1h-.5A2.5 2.5 0 0 1 2 14.5V14a.5.5 0 0 1 .5-.5M9 16a.5.5 0 0 1 0 1H7a.5.5 0 0 1 0-1zm4 0a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1zm4.5-2.5a.5.5 0 0 1 .5.5v.5a2.5 2.5 0 0 1-2.5 2.5H15a.5.5 0 0 1 0-1h.5a1.5 1.5 0 0 0 1.5-1.5V14a.5.5 0 0 1 .5-.5M15.25 7a.75.75 0 0 1 .75.75v6.5a.75.75 0 0 1-.75.75H4.75a.75.75 0 0 1-.75-.75v-4.5A.75.75 0 0 1 4.75 9h2.008a3 3 0 0 0 2.12-.879l.902-.901a.75.75 0 0 1 .53-.22zM2.5 10a.5.5 0 0 1 .5.5V12a.5.5 0 0 1-1 0v-1.5a.5.5 0 0 1 .5-.5m15 0a.5.5 0 0 1 .5.5V12a.5.5 0 0 1-1 0v-1.5a.5.5 0 0 1 .5-.5M7.086 3a1.5 1.5 0 0 1 1.06.44l1.708 1.706a.5.5 0 0 1 0 .708L8.146 7.56a1.5 1.5 0 0 1-1.06.44H6.5a.5.5 0 0 1 0-1h.586a.5.5 0 0 0 .353-.146L8.793 5.5L7.439 4.146A.5.5 0 0 0 7.086 4H4.5A1.5 1.5 0 0 0 3 5.5V7h1.5a.5.5 0 0 1 0 1H3v.5a.5.5 0 0 1-1 0v-3A2.5 2.5 0 0 1 4.5 3zM15.5 5A2.5 2.5 0 0 1 18 7.5v1a.5.5 0 0 1-1 0v-1A1.5 1.5 0 0 0 15.5 6H15a.5.5 0 0 1 0-1zM13 5a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1z");
}

</style>
