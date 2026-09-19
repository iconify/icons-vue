<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8q57kbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8q57kbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:close-square-light" /></template>
