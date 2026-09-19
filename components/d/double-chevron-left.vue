<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx8vx6qnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="cx8vx6qnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:double-chevron-left" /></template>
