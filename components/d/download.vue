<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm0nqy8gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mm0nqy8gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:download" /></template>
