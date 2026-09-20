<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gel_m_b1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gel_m_b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-shield-fill" /></template>
