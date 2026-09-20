<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th7z8fm7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th7z8fm7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-sun-tear" /></template>
