<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auvh3l48q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="auvh3l48q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:download-add" /></template>
