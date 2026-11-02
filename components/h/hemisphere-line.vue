<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_8agt07l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_8agt07l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hemisphere-line" /></template>
