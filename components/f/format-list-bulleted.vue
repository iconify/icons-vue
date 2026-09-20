<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2iq2ocoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-list-bulleted" /></template>
<style>
.b2iq2ocoi {
  fill: currentColor;
  d: path("M9.616 18.5v-1H20v1zm0-6v-1H20v1zm0-6v-1H20v1zM5.327 19.327q-.547 0-.937-.39T4 18t.39-.937t.937-.39t.937.39t.39.937t-.39.937t-.937.39m0-6q-.547 0-.937-.386Q4 12.556 4 12t.39-.941t.937-.386t.937.386q.39.385.39.941t-.39.941t-.937.386m-.941-6.386Q4 6.556 4 6t.386-.941t.941-.386t.941.386q.386.385.386.941t-.386.941q-.385.386-.941.386t-.941-.386");
}

</style>
