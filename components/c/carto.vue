<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1m_ek77t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1m_ek77t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:carto" /></template>
