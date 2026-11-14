<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6tascb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:apple" /></template>
<style>
.h6tascb3j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.853 7.12q1.772-.723 3.683.278Q19.25 8.82 19.25 12.5q0 3.263-1.622 5.753Q16.003 20.75 14 20.75q-.735 0-1.63-.371q-.312-.129-.37-.129t-.37.129q-.895.371-1.63.371q-2.003 0-3.628-2.497Q4.75 15.763 4.75 12.5q0-3.68 2.714-5.102q2.006-1.051 3.859-.202q.438-3.659 3.495-4.424q.145-.036.292-.014q.148.022.276.099t.217.197q.088.119.125.264q.036.145.014.292q-.022.148-.099.276t-.197.217t-.264.125q-1.931.482-2.329 2.892");
}

</style>
