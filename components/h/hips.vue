<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5fms6pzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="c5fms6pzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:hips" /></template>
