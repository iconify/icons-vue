<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfus-81oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfus-81oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:left-line" /></template>
