<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="n30kgubxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:briefcase-12-filled" /></template>
<style>
.n30kgubxd {
  fill: currentColor;
  d: path("M6.75 1C7.44 1 8 1.56 8 2.25V3h1a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h1v-.75C4 1.56 4.56 1 5.25 1zm-1.5 1a.25.25 0 0 0-.25.25V3h2v-.75A.25.25 0 0 0 6.75 2z");
}

</style>
