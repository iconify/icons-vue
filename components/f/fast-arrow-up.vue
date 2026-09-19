<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz7wivbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz7wivbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fast-arrow-up" /></template>
