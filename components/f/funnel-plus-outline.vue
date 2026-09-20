<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_91e6x2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_91e6x2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:funnel-plus-outline" /></template>
