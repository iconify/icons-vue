<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpmw0obfn.css';
import '../../css/x/x83nu3j7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jpmw0obfn"/><path class="x83nu3j7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:information-square-filled" /></template>
