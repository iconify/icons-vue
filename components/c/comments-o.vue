<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo3hbbpap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="jo3hbbpap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:comments-o" /></template>
