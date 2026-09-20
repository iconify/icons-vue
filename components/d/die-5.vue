<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux-84ebfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux-84ebfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:die-5" /></template>
