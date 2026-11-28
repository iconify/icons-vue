<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0yuwq6mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary y0yuwq6mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:activity-duotone" /></template>
