<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogo0ji8gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogo0ji8gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:highlight" /></template>
