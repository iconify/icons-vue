<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7k76abce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7k76abce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:loop-1" /></template>
