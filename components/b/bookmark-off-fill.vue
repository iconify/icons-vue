<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaps6tbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaps6tbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-off-fill" /></template>
