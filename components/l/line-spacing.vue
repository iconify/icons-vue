<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnx33c0jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fnx33c0jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:line-spacing" /></template>
