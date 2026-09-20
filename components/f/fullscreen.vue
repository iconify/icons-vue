<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h74cu0bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h74cu0bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:fullscreen" /></template>
