<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_4luze_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_4luze_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:github-solid" /></template>
