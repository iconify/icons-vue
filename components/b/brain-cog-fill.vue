<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq40a4d6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq40a4d6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brain-cog-fill" /></template>
