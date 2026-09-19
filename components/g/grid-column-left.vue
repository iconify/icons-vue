<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttk0ucc9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttk0ucc9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-column-left" /></template>
