<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le_804bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le_804bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:briefcase-2-line" /></template>
