<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="d84t0-bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-cube-28-filled" /></template>
<style>
.d84t0-bxo {
  fill: currentColor;
  d: path("M14 4a7 7 0 0 0-6.931 6.017A5.5 5.5 0 0 0 7.5 21H13v-4.08a3 3 0 0 1 1.702-2.706l4-1.92a3 3 0 0 1 2.596 0l4 1.92q.346.168.632.409a5.5 5.5 0 0 0-4.999-4.606A7 7 0 0 0 14 4m12 18.08v-5.16a2 2 0 0 0-1.135-1.804l-4-1.92a2 2 0 0 0-1.73 0l-4 1.92A2 2 0 0 0 14 16.919v5.161a2 2 0 0 0 1.135 1.804l4 1.92a2 2 0 0 0 1.73 0l4-1.92A2 2 0 0 0 26 22.08m-9.95-5.296a.5.5 0 0 1 .666-.235L20 18.125l3.284-1.576a.5.5 0 1 1 .432.902L20.5 18.994V23a.5.5 0 0 1-1 0v-4.006l-3.216-1.543a.5.5 0 0 1-.235-.667");
}

</style>
