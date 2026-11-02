<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6j_1ipvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6j_1ipvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dress-fill" /></template>
