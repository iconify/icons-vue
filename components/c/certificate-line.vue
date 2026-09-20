<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc_bc1-ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc_bc1-ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:certificate-line" /></template>
