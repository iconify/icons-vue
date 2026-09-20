<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3z62osle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3z62osle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:community-line" /></template>
