<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkjb51frr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkjb51frr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gauge-round" /></template>
