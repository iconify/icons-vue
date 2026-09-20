<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j9czmpd3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:local-language-globe-20-filled" /></template>
<style>
.j9czmpd3d {
  fill: currentColor;
  d: path("M8 10a.5.5 0 0 1 .468.324l2.25 6a.5.5 0 0 1-.936.352L9.153 15H6.847l-.63 1.676a.5.5 0 0 1-.935-.352l2.25-6l.032-.07A.5.5 0 0 1 8 10m7.5 0a.5.5 0 0 1 .416.777L15.101 12H17.5a.5.5 0 0 1 0 1H15v2a1 1 0 0 1-1 1h-.5a.5.5 0 0 1 0-1h.5v-2h-2.5a.5.5 0 0 1 0-1H14a.5.5 0 0 1 .084-.277l.481-.723H12.5a.5.5 0 0 1 0-1zm-8.278 4h1.556L8 11.923zm-3.21-6.5c.068 1.654.47 3.118 1.074 4.12A5 5 0 0 1 2.024 7.5zm4.975 0a10 10 0 0 1-.222 1.71a1.497 1.497 0 0 0-2.124.656l-.045.108l-.508 1.353a4 4 0 0 1-.315-.531c-.409-.818-.7-1.97-.76-3.296zM14 7a.5.5 0 0 1 .5.5V8h3a.5.5 0 0 1 .5.5V10a.5.5 0 0 1-1 0V9h-6v1a.5.5 0 0 1-1 0V8.5a.5.5 0 0 1 .5-.5h3v-.5A.5.5 0 0 1 14 7M5.086 2.38c-.603 1-1.006 2.465-1.074 4.12H2.024a5 5 0 0 1 3.062-4.12M7 2c.246 0 .737.225 1.227 1.204c.409.818.7 1.97.76 3.296H5.013c.06-1.326.351-2.478.76-3.296C6.263 2.225 6.754 2 7 2m1.913.38a5 5 0 0 1 3.063 4.12H9.988c-.068-1.655-.472-3.12-1.075-4.12");
}

</style>
