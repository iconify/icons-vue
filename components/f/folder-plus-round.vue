<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym4d8ub0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym4d8ub0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-plus-round" /></template>
