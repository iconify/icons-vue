<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5u6vqnyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j5u6vqnyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:jira" /></template>
