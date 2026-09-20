<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7m_lmbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7m_lmbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lmms" /></template>
