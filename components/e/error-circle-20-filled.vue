<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jl7hk-bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:error-circle-20-filled" /></template>
<style>
.jl7hk-bet {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m0 10.5a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5M10 6a.5.5 0 0 0-.492.41L9.5 6.5V11l.008.09a.5.5 0 0 0 .984 0L10.5 11V6.5l-.008-.09A.5.5 0 0 0 10 6");
}

</style>
