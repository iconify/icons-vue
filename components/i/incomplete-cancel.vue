<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz8ykxbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mz8ykxbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:incomplete-cancel" /></template>
