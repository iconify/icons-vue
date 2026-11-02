<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc0h5zb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc0h5zb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-check-4-line" /></template>
