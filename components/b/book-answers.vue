<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv4q6-env.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nv4q6-env"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:book-answers" /></template>
