<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpwvv1mvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calculator-24-regular" /></template>
<style>
.gpwvv1mvd {
  fill: currentColor;
  d: path("M7 7a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2zm2-.5a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h6a.5.5 0 0 0 .5-.5V7a.5.5 0 0 0-.5-.5zm-.75 8a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m1.25 2.75a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0m6.25-2.75a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5M17 17.25a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0m-5-2.75a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m1.25 2.75a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0M7.25 2A3.25 3.25 0 0 0 4 5.25v13.5A3.25 3.25 0 0 0 7.25 22h9.5A3.25 3.25 0 0 0 20 18.75V5.25A3.25 3.25 0 0 0 16.75 2zM5.5 5.25c0-.966.784-1.75 1.75-1.75h9.5c.966 0 1.75.784 1.75 1.75v13.5a1.75 1.75 0 0 1-1.75 1.75h-9.5a1.75 1.75 0 0 1-1.75-1.75z");
}

</style>
