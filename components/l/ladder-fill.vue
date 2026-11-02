<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn7_0n8ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn7_0n8ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ladder-fill" /></template>
