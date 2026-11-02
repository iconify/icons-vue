<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2do23bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2do23bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:kingkey-100-tower-line" /></template>
