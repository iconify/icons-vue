<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq_irubvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq_irubvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:funnel-outline" /></template>
