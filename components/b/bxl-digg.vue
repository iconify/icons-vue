<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_mj50i8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_mj50i8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-digg" /></template>
