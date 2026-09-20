<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoe_m_b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoe_m_b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:hourglass" /></template>
