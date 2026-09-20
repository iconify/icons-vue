<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp6yps19e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp6yps19e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:eraser" /></template>
