<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq7dv5egz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq7dv5egz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:anticlockwise-fill" /></template>
