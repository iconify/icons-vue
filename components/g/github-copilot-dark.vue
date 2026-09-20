<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1zld5b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":208};
const content = `<path class="j1zld5b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:github-copilot-dark" /></template>
