<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynpf76igj.css';
import '../../css/o/o-oqurbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ynpf76igj"/><path class="o-oqurbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flow-modeler" /></template>
