<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d57gu2bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d57gu2bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-2-cog" /></template>
