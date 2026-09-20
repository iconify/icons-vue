<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plwo88b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="plwo88b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:inline-left" /></template>
