<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r19iztq9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mail-person-outline-sharp" /></template>
<style>
.r19iztq9u {
  fill: currentColor;
  d: path("M4 6v12v-8v.275zM2 20V4h20v6h-2V8l-8 5l-8-5v10h8v2zm16-4q-.825 0-1.412-.587T16 14t.588-1.412T18 12t1.413.588T20 14t-.587 1.413T18 16m-4 4v-.575q0-.6.325-1.1t.9-.75q.7-.275 1.363-.425t1.487-.15q.725 0 1.425.15t1.275.425t.9.763t.325 1.087V20zm-2-9l8-5H4z");
}

</style>
