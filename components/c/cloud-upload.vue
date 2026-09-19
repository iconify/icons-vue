<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llc3hsxpl.css';
import '../../css/j/j1alc3bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="llc3hsxpl"/><path class="j1alc3bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-upload" /></template>
