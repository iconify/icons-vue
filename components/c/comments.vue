<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du4ls38az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="du4ls38az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:comments" /></template>
