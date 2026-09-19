<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llf0wacfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llf0wacfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:edge" /></template>
