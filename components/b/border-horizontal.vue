<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm8holt9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jm8holt9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:border-horizontal" /></template>
