<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frr12ubyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frr12ubyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ink-plus" /></template>
