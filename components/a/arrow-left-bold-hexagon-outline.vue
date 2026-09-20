<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc_irebcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc_irebcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-bold-hexagon-outline" /></template>
