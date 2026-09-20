<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz_t73nab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz_t73nab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:eraser" /></template>
