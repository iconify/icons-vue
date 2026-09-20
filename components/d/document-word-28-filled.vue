<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="o8cfedbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-word-28-filled" /></template>
<style>
.o8cfedbdd {
  fill: currentColor;
  d: path("M11.75 13A2.25 2.25 0 0 1 14 15.25v8.5A2.25 2.25 0 0 1 11.75 26h-8.5A2.25 2.25 0 0 1 1 23.75v-8.5A2.25 2.25 0 0 1 3.25 13zM14 10a2 2 0 0 0 2 2h7.999l.001.078V23.6a2.4 2.4 0 0 1-2.4 2.4h-7.508A3.24 3.24 0 0 0 15 23.75v-8.5A3.25 3.25 0 0 0 11.75 12H4V4.4A2.4 2.4 0 0 1 6.4 2H14zm-3.615 5.751l-.935 4.95l-.996-4.95H6.502l-.952 4.95l-.958-4.95H3l1.553 7.499h1.949l.998-4.5l.954 4.5l1.93-.001L12 15.75zM15.5 2.475q.139.104.264.228l7.43 7.43q.171.172.308.367H16a.5.5 0 0 1-.5-.5z");
}

</style>
