<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytwuz5yos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="ytwuz5yos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:info-outline" /></template>
