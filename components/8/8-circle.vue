<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfe9tcbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wfe9tcbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:8-circle" /></template>
