<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8bxy215p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8bxy215p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grape-line" /></template>
