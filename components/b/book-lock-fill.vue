<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zshp-2y7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zshp-2y7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-lock-fill" /></template>
