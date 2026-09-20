<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyi0vrbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyi0vrbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chart-box" /></template>
