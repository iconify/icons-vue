<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbnbl3m4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbnbl3m4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-campaignmonitor" /></template>
