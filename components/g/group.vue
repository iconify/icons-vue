<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-azsssci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z-azsssci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:group" /></template>
