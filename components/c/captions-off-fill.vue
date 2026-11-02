<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5zf0ibaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5zf0ibaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:captions-off-fill" /></template>
