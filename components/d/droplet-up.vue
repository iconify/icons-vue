<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxg6ctbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxg6ctbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-up" /></template>
