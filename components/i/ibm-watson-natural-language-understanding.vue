<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu-ss8biv.css';
import '../../css/z/zg21q53ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hu-ss8biv"/><path class="zg21q53ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watson-natural-language-understanding" /></template>
