<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oa43r042w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-csv-20-regular" /></template>
<style>
.oa43r042w {
  fill: currentColor;
  d: path("M3 12a2 2 0 0 1 2 2a.5.5 0 0 1-1 0a1 1 0 1 0-2 0v2a1 1 0 1 0 2 0a.5.5 0 0 1 1 0a2 2 0 1 1-4 0v-2a2 2 0 0 1 2-2m4.5 0A1.5 1.5 0 0 1 9 13.5a.5.5 0 0 1-.99.1l-.02-.2a.5.5 0 0 0-.99.1v.382a.5.5 0 0 0 .276.447l.895.447A1.5 1.5 0 0 1 9 16.118v.382a1.5 1.5 0 0 1-3 0a.5.5 0 0 1 .99-.1l.02.2a.5.5 0 0 0 .99-.1v-.382a.5.5 0 0 0-.276-.447l-.895-.447A1.5 1.5 0 0 1 6 13.882V13.5A1.5 1.5 0 0 1 7.5 12m5.528.335a.5.5 0 1 1 .944.33l-1.75 5a.5.5 0 0 1-.944 0l-1.75-5a.5.5 0 0 1 .944-.33l1.278 3.651zM10.586 2a1.5 1.5 0 0 1 1.06.44l3.914 3.914a1.5 1.5 0 0 1 .44 1.06V16a2 2 0 0 1-1.773 1.985l-.046.005Q14.09 18 14 18h-.836l.002-.004l.349-.996H14a1 1 0 0 0 1-1V8h-3.5A1.5 1.5 0 0 1 10 6.5V3H6a1 1 0 0 0-1 1v7.764a3 3 0 0 0-1-.593V4a2 2 0 0 1 2-2zM11 6.5a.5.5 0 0 0 .5.5h3.293L11 3.207z");
}

</style>
