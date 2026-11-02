<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khz5z_bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khz5z_bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dot-fill" /></template>
