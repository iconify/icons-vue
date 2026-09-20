<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k44dg_bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k44dg_bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camera-line" /></template>
