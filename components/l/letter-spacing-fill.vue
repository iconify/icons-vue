<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejm67ybkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejm67ybkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:letter-spacing-fill" /></template>
