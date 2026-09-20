<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_wl7cckw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_wl7cckw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:camera-2-line" /></template>
