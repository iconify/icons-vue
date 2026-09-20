<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy8ogs3oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy8ogs3oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:line-height-line" /></template>
