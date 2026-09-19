<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izv086fqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="izv086fqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:key-values" /></template>
