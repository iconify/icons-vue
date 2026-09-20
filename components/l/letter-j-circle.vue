<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5yc4ob3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5yc4ob3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-j-circle" /></template>
