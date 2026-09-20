<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j969lxbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j969lxbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:botble-cms" /></template>
