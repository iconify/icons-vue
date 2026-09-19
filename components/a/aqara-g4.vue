<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di-r0pzwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di-r0pzwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-g4" /></template>
