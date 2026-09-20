<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckh_tgrcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:identity-platform-rounded" /></template>
<style>
.ckh_tgrcq {
  fill: currentColor;
  d: path("M11.162 19.666q.384.242.838.239t.839-.246l4.28-2.62q-1.153-.741-2.453-1.14T12 15.5t-2.668.409q-1.303.408-2.482 1.124zm2.967-8.037Q15 10.758 15 9.5t-.871-2.129T12 6.5t-2.129.871T9 9.5t.871 2.129T12 12.5t2.129-.871m-2.967 9.188l-6.385-3.896q-.373-.217-.575-.59T4 15.529V8.47q0-.429.202-.802t.575-.59l6.385-3.896q.384-.242.838-.242t.839.242l6.384 3.896q.373.217.575.59T20 8.47v7.058q0 .429-.202.802t-.575.59l-6.384 3.896q-.385.243-.839.243t-.838-.243");
}

</style>
