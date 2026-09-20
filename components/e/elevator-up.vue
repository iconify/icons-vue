<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxbldn1_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxbldn1_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:elevator-up" /></template>
