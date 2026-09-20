<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxwb6_eza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxwb6_eza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:allergen-outline" /></template>
