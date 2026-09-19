<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0mipjbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0mipjbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:drawing-compass" /></template>
