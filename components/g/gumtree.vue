<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly8ue0hvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly8ue0hvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gumtree" /></template>
