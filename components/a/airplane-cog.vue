<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bao4k39lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bao4k39lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airplane-cog" /></template>
