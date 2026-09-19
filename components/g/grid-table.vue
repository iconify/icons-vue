<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw8xyyw2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw8xyyw2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:grid-table" /></template>
