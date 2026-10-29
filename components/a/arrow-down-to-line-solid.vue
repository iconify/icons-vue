<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogh3b21vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogh3b21vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-down-to-line-solid" /></template>
