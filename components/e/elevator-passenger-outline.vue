<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvrua7b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvrua7b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:elevator-passenger-outline" /></template>
