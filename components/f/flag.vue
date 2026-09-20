<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvi4wn27q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hvi4wn27q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:flag" /></template>
