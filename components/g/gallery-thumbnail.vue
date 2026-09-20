<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6kqbfbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gallery-thumbnail" /></template>
<style>
.a6kqbfbcm {
  fill: currentColor;
  d: path("M4.116 18q-.667 0-1.141-.475t-.475-1.14v-8.77q0-.666.475-1.14T4.115 6h8.77q.666 0 1.14.475t.475 1.14v8.77q0 .666-.475 1.14t-1.14.475zm13.201-7q-.357 0-.587-.23t-.23-.587V6.817q0-.357.23-.587t.587-.23h3.366q.357 0 .587.23t.23.587v3.366q0 .358-.23.587t-.587.23zM4.692 14.904h7.616l-2.433-3.25L8 14.154l-1.375-1.825zM17.317 18q-.357 0-.587-.23t-.23-.587v-3.366q0-.357.23-.587t.587-.23h3.366q.357 0 .587.23t.23.587v3.366q0 .358-.23.587t-.587.23z");
}

</style>
