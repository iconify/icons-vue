<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nt1re5l8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-dismiss-20-filled" /></template>
<style>
.nt1re5l8u {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m1-5A2.5 2.5 0 0 1 18 7.5v2.757A5.5 5.5 0 0 0 9.602 17H4.5A2.5 2.5 0 0 1 2 14.5V8h5.086a1.5 1.5 0 0 0 1.06-.44L10.707 5zm.854 7.647a.5.5 0 0 0-.707 0L14.5 13.793l-1.146-1.146a.5.5 0 1 0-.707.707l1.146 1.146l-1.146 1.146a.5.5 0 1 0 .707.707l1.146-1.146l1.146 1.146a.5.5 0 1 0 .707-.707L15.208 14.5l1.146-1.146a.5.5 0 0 0 0-.707M6.982 3c.464 0 .91.185 1.238.513l1.28 1.28l-2.06 2.06A.5.5 0 0 1 7.085 7H2V5.5A2.5 2.5 0 0 1 4.5 3z");
}

</style>
