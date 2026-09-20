<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj5f_ybll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj5f_ybll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-horizontal-space-around-sharp" /></template>
