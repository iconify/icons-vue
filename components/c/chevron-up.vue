<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqcndx14s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqcndx14s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chevron-up" /></template>
