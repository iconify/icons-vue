<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n63k8io3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-briefcase-24-regular" /></template>
<style>
.n63k8io3o {
  fill: currentColor;
  d: path("M18.5 20a.5.5 0 0 1-.5.5h-5v1q0 .257-.05.5H18a2 2 0 0 0 2-2V9.828a2 2 0 0 0-.586-1.414l-5.829-5.828A2.05 2.05 0 0 0 12.172 2H6a2 2 0 0 0-2 2v7.104Q4.358 11 4.75 11h.75V4a.5.5 0 0 1 .5-.5h6V8a2 2 0 0 0 2 2h4.5zm-5-15.379L17.378 8.5H14a.5.5 0 0 1-.5-.5zM3 15.001h-.5A1.5 1.5 0 0 0 1 16.5v5A1.5 1.5 0 0 0 2.5 23h8a1.5 1.5 0 0 0 1.5-1.5v-5a1.5 1.5 0 0 0-1.5-1.5H10v-1.25A1.75 1.75 0 0 0 8.25 12h-3.5A1.75 1.75 0 0 0 3 13.75zm1.5-1.251a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25V15h-4z");
}

</style>
