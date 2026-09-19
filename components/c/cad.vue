<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4nt8lb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e4nt8lb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cad" /></template>
