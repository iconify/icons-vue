<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6vskqo0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f6vskqo0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:decline" /></template>
