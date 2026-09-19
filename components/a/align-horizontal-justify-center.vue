<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_hz5eaxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_hz5eaxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-horizontal-justify-center" /></template>
