<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hec03xb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hec03xb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hands-clapping-line" /></template>
