<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxkkv7aav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxkkv7aav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-bold-hexagon-outline" /></template>
