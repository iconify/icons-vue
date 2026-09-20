<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg2686ecp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg2686ecp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-bar-to-right-dashed" /></template>
