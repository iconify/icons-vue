<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bere3e6ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bere3e6ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-floor-ground" /></template>
