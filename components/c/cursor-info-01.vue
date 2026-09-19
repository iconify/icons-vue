<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2_m_eb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2_m_eb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cursor-info-01" /></template>
