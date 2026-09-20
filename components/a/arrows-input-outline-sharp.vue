<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4l8tvb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrows-input-outline-sharp" /></template>
<style>
.e4l8tvb7k {
  fill: currentColor;
  d: path("m4.4 20.308l-.708-.708l3.6-3.6H4v-1h5v5H8v-3.292zm15.2 0l-3.6-3.6V20h-1v-5h5v1h-3.292l3.6 3.6zM4 9V8h3.292l-3.6-3.6l.708-.708l3.6 3.6V4h1v5zm11 0V4h1v3.292l3.6-3.6l.708.708l-3.6 3.6H20v1zm-3 4.327q-.547 0-.937-.386q-.39-.385-.39-.941t.39-.941t.937-.386t.937.386q.39.385.39.941t-.39.941t-.937.386");
}

</style>
