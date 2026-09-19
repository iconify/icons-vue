<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrkzq_4jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nrkzq_4jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-yy" /></template>
