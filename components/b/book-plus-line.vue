<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo149e-4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo149e-4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:book-plus-line" /></template>
