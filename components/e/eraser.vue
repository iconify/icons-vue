<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byl30kbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="byl30kbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:eraser" /></template>
