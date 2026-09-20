<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd9rnlwhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hd9rnlwhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:kebab-horizontal-16" /></template>
