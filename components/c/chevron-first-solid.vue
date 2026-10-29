<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiobo4jps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiobo4jps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-first-solid" /></template>
