<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv03d2joh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1472,"height":1536};
const content = `<path class="iv03d2joh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:flask" /></template>
