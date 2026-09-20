<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-h1us7qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j-h1us7qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:bottom-align-outline" /></template>
