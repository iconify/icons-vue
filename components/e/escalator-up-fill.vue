<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs_1f4bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs_1f4bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:escalator-up-fill" /></template>
