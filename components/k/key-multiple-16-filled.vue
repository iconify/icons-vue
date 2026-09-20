<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x45oo6v-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:key-multiple-16-filled" /></template>
<style>
.x45oo6v-t {
  fill: currentColor;
  d: path("M7.96 1.03Q7.734 1 7.5 1a3.5 3.5 0 0 0-3.426 4.219L1.146 8.146A.5.5 0 0 0 1 8.5v3a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 .5-.5v-1h1.5A.5.5 0 0 0 6 10V8.707l.877-.877A5 5 0 0 1 6 5a4.99 4.99 0 0 1 1.96-3.97M7 5a4 4 0 1 1 6 3.465v1.828l.854.853a.5.5 0 0 1 0 .708l-.647.646l.647.646a.5.5 0 0 1-.054.754l-2 1.5a.5.5 0 0 1-.6 0l-2-1.5a.5.5 0 0 1-.2-.4V8.465A4 4 0 0 1 7 5m4.75-1a.75.75 0 1 0-1.5 0a.75.75 0 0 0 1.5 0");
}

</style>
