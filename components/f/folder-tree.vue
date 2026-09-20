<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjvwbgbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjvwbgbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-tree" /></template>
