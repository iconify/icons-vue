<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kon67vble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kon67vble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-bold-hexagon-outline" /></template>
