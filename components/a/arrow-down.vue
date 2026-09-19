<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_ugq-blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_ugq-blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-down" /></template>
