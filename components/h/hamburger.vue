<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc9rh9xuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pc9rh9xuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:hamburger" /></template>
