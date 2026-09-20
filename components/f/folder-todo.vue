<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swsj6o8lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="swsj6o8lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:folder-todo" /></template>
