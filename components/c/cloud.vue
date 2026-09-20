<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w97go_krl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="w97go_krl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:cloud" /></template>
