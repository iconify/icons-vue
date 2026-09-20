<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhx461bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhx461bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:arrow-left-box" /></template>
