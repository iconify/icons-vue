<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbnptoigz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbnptoigz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:git-compare-line" /></template>
