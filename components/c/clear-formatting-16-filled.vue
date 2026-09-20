<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hr579cbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clear-formatting-16-filled" /></template>
<style>
.hr579cbgy {
  fill: currentColor;
  d: path("M2.958 2a.75.75 0 0 0-.727.568l-.236.945a.75.75 0 0 0 1.455.363l.094-.376h2.024l-1.225 7h-.388a.75.75 0 0 0 0 1.5h2.067a5.6 5.6 0 0 1 .068-1.499l-.044-.001h-.18l1.224-7h2.227l-.003.013a.75.75 0 0 0 1.455.363l.236-.944A.75.75 0 0 0 10.278 2zM1.75 12.5h4.34A5.5 5.5 0 0 0 6.6 14H1.75a.75.75 0 0 1 0-1.5m14.25-1a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-2.646-1.146a.5.5 0 0 0-.708-.708L11.5 10.793l-1.146-1.147a.5.5 0 0 0-.708.708l1.147 1.146l-1.147 1.146a.5.5 0 0 0 .708.708l1.146-1.147l1.146 1.147a.5.5 0 0 0 .708-.708L12.207 11.5z");
}

</style>
