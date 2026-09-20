<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5cov6bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v5cov6bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:bell" /></template>
