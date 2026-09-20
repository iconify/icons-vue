<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up7inibzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up7inibzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:computer-camer-line" /></template>
