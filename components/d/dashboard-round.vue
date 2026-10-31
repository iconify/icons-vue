<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiq5bukpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiq5bukpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dashboard-round" /></template>
