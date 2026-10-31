<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzp-m_bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzp-m_bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:droplet-fill-round" /></template>
