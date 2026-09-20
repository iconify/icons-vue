<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt24h6bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt24h6bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cart-off" /></template>
