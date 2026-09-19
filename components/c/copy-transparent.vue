<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j66vk4b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j66vk4b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:copy-transparent" /></template>
