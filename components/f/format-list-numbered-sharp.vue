<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1j0_db5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-list-numbered-sharp" /></template>
<style>
.u1j0_db5w {
  fill: currentColor;
  d: path("M3 22v-1.5h2.5v-.75H4v-1.5h1.5v-.75H3V16h4v2.25L6 19l1 .75V22zm0-7v-3.75h2.5v-.75H3V9h4v3.75H4.5v.75H7V15zm1.5-7V3.5H3V2h3v6zM9 19v-2h12v2zm0-6v-2h12v2zm0-6V5h12v2z");
}

</style>
