<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwf-2hout.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwf-2hout"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dashboard-3-line" /></template>
