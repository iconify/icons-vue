<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfve_zbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jfve_zbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:git" /></template>
