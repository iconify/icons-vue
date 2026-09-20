<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk2gju-pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk2gju-pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chart-waterfall" /></template>
