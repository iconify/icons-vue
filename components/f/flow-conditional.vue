<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jphow5moh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jphow5moh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flow-conditional" /></template>
