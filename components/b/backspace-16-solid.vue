<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3-d0ybjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j3-d0ybjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:backspace-16-solid" /></template>
