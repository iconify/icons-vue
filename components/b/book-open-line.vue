<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr9p9rb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr9p9rb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:book-open-line" /></template>
