<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1har9pwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-inbox-dismiss-24-filled" /></template>
<style>
.k1har9pwq {
  fill: currentColor;
  d: path("M22 6.5a5.5 5.5 0 1 1-11 0a5.5 5.5 0 0 1 11 0m-7.146-2.354a.5.5 0 0 0-.708.708L15.793 6.5l-1.647 1.646a.5.5 0 0 0 .708.708L16.5 7.207l1.646 1.647a.5.5 0 0 0 .708-.708L17.207 6.5l1.647-1.646a.5.5 0 0 0-.708-.708L16.5 5.793zM19.5 14v-1.732A6.5 6.5 0 0 0 21 11.19v7.56A3.25 3.25 0 0 1 17.75 22H6.25A3.25 3.25 0 0 1 3 18.75V7.25A3.25 3.25 0 0 1 6.25 4h4.248a6.5 6.5 0 0 0-.422 1.5H6.25A1.75 1.75 0 0 0 4.5 7.25V14H9a.75.75 0 0 1 .743.648l.007.102a2.25 2.25 0 0 0 4.5 0A.75.75 0 0 1 15 14z");
}

</style>
