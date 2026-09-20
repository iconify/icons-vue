<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="giihj05_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-shield-28-filled" /></template>
<style>
.giihj05_m {
  fill: currentColor;
  d: path("M20.901 14.23a.895.895 0 0 1 1.198 0c.797.769 2.33 1.993 4.215 2.244c.376.05.686.336.686.695v3.355c0 4.51-4.374 6.146-5.32 6.448a.6.6 0 0 1-.359 0c-.946-.302-5.32-1.938-5.321-6.448V17.17c0-.359.31-.645.686-.695c1.884-.251 3.418-1.475 4.215-2.245M14 2a5.5 5.5 0 0 1 5.5 5.5v2.509a3.75 3.75 0 0 1 3.498 3.69l-.206-.19l-.137-.118a1.904 1.904 0 0 0-2.31 0l-.138.119c-.704.679-1.926 1.635-3.363 1.924l-.29.048c-.671.09-1.4.596-1.531 1.422a1.5 1.5 0 1 0-.023 2.21v1.41l.016.483c.142 2.299 1.294 3.917 2.542 4.993H8.75A3.75 3.75 0 0 1 5 22.25v-8.5a3.75 3.75 0 0 1 3.5-3.741V7.5A5.5 5.5 0 0 1 14 2m0 1.5a4 4 0 0 0-4 4V10h8V7.5a4 4 0 0 0-4-4");
}

</style>
