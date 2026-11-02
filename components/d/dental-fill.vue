<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m64y0ybiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m64y0ybiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dental-fill" /></template>
