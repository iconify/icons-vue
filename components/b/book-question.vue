<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg8js6q3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg8js6q3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:book-question" /></template>
