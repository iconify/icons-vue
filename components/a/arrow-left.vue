<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n--fw0uon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n--fw0uon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:arrow-left" /></template>
