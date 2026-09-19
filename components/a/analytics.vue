<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwwl4pngj.css';
import '../../css/c/c7npnxbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uwwl4pngj"/><path class="c7npnxbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:analytics" /></template>
