<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcjwu4xpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rcjwu4xpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:flask-dark" /></template>
