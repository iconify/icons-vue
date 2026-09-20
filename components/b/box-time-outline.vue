<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejjotehzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejjotehzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-time-outline" /></template>
