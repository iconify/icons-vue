<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1f8rccia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1f8rccia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:filter-off-round" /></template>
