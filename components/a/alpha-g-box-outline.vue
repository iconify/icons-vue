<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st3e-o8vj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st3e-o8vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-g-box-outline" /></template>
