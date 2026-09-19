<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc61ku0nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":432};
const content = `<path class="yc61ku0nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:hourglass-outline" /></template>
