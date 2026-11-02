<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epxcznbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epxcznbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-check-2-fill" /></template>
