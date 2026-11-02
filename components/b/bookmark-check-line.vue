<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjhzmob8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjhzmob8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-check-line" /></template>
