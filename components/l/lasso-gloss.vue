<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-h0aogne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-h0aogne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lasso-gloss" /></template>
