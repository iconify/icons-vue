<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji7x0bcjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ji7x0bcjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-ppt" /></template>
