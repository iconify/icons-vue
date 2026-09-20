<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t25tctdjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t25tctdjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:book-16" /></template>
