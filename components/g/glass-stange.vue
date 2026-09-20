<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljf0g-bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljf0g-bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:glass-stange" /></template>
