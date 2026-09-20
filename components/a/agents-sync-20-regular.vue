<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kvt23-ivg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-sync-20-regular" /></template>
<style>
.kvt23-ivg {
  fill: currentColor;
  d: path("M15.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M9.498 2a.5.5 0 1 1 0 1h-2.81a.75.75 0 0 0-.635.35L2.11 9.6a.75.75 0 0 0 0 .8l3.868 6.133c.183.29.503.467.846.467h.02a1 1 0 0 0 .967-.742l3.406-12.774A2 2 0 0 1 13.15 2h.02a2 2 0 0 1 1.692.934l3.868 6.132c.226.357.309.775.252 1.177a5.5 5.5 0 0 0-1.148-.724l-3.817-6.052A1 1 0 0 0 13.17 3h-.02a1 1 0 0 0-.966.742L8.778 16.516A2 2 0 0 1 6.846 18h-.02a2 2 0 0 1-1.692-.933l-3.868-6.133a1.75 1.75 0 0 1 0-1.868l3.941-6.25A1.75 1.75 0 0 1 6.687 2zM13.5 15a.5.5 0 0 0-.5.5V17a.5.5 0 0 0 1 0v-.152a3 3 0 0 0 2.624.183c.373-.15.712-.375.997-.66a.5.5 0 1 0-.707-.707a2 2 0 0 1-2.382.336H15a.5.5 0 1 0 0-1zm4-3.5a.5.5 0 0 0-.5.5v.152a3 3 0 0 0-1.447-.402a3 3 0 0 0-2.174.879a.5.5 0 0 0 .707.707A2 2 0 0 1 16.469 13H16a.5.5 0 0 0 0 1h1.5a.5.5 0 0 0 .5-.5V12a.5.5 0 0 0-.5-.5");
}

</style>
