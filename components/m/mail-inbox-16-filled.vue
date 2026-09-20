<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mmu7fxbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-inbox-16-filled" /></template>
<style>
.mmu7fxbrq {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zM13 8V4.5A1.5 1.5 0 0 0 11.5 3h-7A1.5 1.5 0 0 0 3 4.5V8h2.5a.5.5 0 0 1 .5.5c0 .052.008.162.032.308c.041.247.115.493.228.718c.308.618.843.974 1.74.974s1.432-.356 1.74-.974c.113-.225.187-.47.228-.718c.024-.146.032-.256.032-.308a.5.5 0 0 1 .41-.492L10.5 8z");
}

</style>
