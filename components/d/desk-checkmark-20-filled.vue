<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gmjxoo4et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-checkmark-20-filled" /></template>
<style>
.gmjxoo4et {
  fill: currentColor;
  d: path("M9.602 8q.176.345.398.66V14a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V8zM18 15.5a.5.5 0 0 1-1 0v-5.102a5.5 5.5 0 0 0 1-.656zM5 10a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zm9.5-9a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m2.354 2.646a.5.5 0 0 0-.707 0L13.5 6.293l-.646-.647a.5.5 0 1 0-.707.708l1 1a.5.5 0 0 0 .707 0l3-3a.5.5 0 0 0 0-.708M9.208 4a5.5 5.5 0 0 0 0 3H2V6a2 2 0 0 1 2-2z");
}

</style>
