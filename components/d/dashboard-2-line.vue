<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncrvun0li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncrvun0li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dashboard-2-line" /></template>
