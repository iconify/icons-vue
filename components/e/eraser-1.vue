<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5fssrb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5fssrb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:eraser-1" /></template>
