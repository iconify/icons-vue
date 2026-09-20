<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwhh-p3kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwhh-p3kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cross-fill" /></template>
