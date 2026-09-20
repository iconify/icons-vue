<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ielcc5-zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ielcc5-zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-add-line" /></template>
