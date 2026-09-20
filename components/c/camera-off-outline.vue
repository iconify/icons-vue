<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx0uqebjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx0uqebjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-off-outline" /></template>
