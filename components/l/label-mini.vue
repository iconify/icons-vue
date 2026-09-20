<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4fijebgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l4fijebgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:label-mini" /></template>
