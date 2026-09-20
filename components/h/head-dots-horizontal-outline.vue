<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il-4v9blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il-4v9blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-dots-horizontal-outline" /></template>
