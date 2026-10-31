<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_4b-y3-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_4b-y3-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-left-round" /></template>
