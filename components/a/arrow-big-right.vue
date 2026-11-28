<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgfy8elcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgfy8elcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-big-right" /></template>
