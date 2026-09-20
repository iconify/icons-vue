<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z12x-2b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z12x-2b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eraser-fill" /></template>
