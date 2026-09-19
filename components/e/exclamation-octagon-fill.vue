<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yda77z6gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yda77z6gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:exclamation-octagon-fill" /></template>
