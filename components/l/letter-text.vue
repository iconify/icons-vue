<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6lz5qbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6lz5qbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-text" /></template>
