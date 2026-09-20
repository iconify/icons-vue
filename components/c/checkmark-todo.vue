<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsk7nvgoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="dsk7nvgoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:checkmark-todo" /></template>
