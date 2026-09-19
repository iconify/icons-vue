<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2ndmjbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="m2ndmjbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:centercode" /></template>
