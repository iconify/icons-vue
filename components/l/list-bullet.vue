<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu1ta9w8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hu1ta9w8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:list-bullet" /></template>
