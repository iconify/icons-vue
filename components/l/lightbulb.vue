<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2_2ljb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="h2_2ljb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:lightbulb" /></template>
