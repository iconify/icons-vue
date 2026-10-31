<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt_440i5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt_440i5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-plus-corner-fill-round" /></template>
