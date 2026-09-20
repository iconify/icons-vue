<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-hl0zbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-hl0zbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-close-line" /></template>
