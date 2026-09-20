<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="nqj5qkbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-one-page-multiple-28-filled" /></template>
<style>
.nqj5qkbsx {
  fill: currentColor;
  d: path("M22.502 4.803c.89.455 1.5 1.379 1.5 2.447v13.5c0 2.9-2.35 5.25-5.25 5.25h-9.5a2.75 2.75 0 0 1-2.447-1.5h11.947a3.75 3.75 0 0 0 3.75-3.75zM18.75 2a2.75 2.75 0 0 1 2.75 2.75v16a2.75 2.75 0 0 1-2.75 2.75h-12A2.75 2.75 0 0 1 4 20.75v-16A2.75 2.75 0 0 1 6.75 2zM8.25 17.5a.75.75 0 0 0 0 1.5h9a.75.75 0 0 0 0-1.5zm0-5.5a.75.75 0 0 0 0 1.5h9a.75.75 0 0 0 0-1.5zm0-5.5a.75.75 0 0 0 0 1.5h9a.75.75 0 0 0 0-1.5z");
}

</style>
