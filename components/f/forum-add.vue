<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftdxz_m_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftdxz_m_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:forum-add" /></template>
