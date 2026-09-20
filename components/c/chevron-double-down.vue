<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxkygcs9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxkygcs9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:chevron-double-down" /></template>
