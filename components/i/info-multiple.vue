<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cswyp5p5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cswyp5p5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:info-multiple" /></template>
