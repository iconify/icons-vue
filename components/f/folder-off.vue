<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0hdih8qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f0hdih8qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:folder-off" /></template>
