<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anir5prgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="anir5prgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:inbox" /></template>
