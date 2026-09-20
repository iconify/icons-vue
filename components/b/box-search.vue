<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi5q_jiej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi5q_jiej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-search" /></template>
