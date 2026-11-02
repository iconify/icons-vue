<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjkf7ybdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjkf7ybdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-vertical-fill" /></template>
