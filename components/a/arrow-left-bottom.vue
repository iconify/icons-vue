<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wolcjtiie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wolcjtiie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-bottom" /></template>
