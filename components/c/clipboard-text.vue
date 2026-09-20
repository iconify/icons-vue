<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isyff-8qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isyff-8qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:clipboard-text" /></template>
