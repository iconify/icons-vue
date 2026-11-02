<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky9_qybkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky9_qybkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fishing-hook-line" /></template>
