<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lujr4eb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chemical-bottle" /></template>
<style>
.lujr4eb_w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.25 1.75h-2.5q-2.5 0-2.5 2.5v.5q0 1.581 1 2.162v.687l-4.166 2.777q-.077.051-.139.12q-.063.068-.106.15q-.044.082-.066.172T4.75 11v8.5q0 2.75 2.75 2.75h9q2.75 0 2.75-2.75V11q0-.093-.023-.182q-.022-.09-.066-.172q-.043-.082-.106-.15q-.062-.069-.139-.12L14.75 7.599v-.846q.139-.106.268-.235q.732-.732.732-1.768v-.5q0-1.036-.732-1.768T13.25 1.75m0 5.5V8q0 .093.023.182q.022.09.066.172q.043.082.106.15q.062.069.139.12l4.166 2.777V19.5q0 1.25-1.25 1.25h-9q-1.25 0-1.25-1.25v-8.099l4.166-2.777q.077-.051.139-.12q.063-.068.106-.15q.044-.082.066-.172T10.75 8v-.75zM10 12.75h4q.932 0 1.591.659T16.25 15v2q0 .932-.659 1.591T14 19.25h-4q-2.25 0-2.25-2.25v-2q0-2.25 2.25-2.25");
}

</style>
