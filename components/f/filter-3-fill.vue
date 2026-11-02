<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-hvvacuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-hvvacuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:filter-3-fill" /></template>
