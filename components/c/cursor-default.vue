<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqnd8rbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqnd8rbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cursor-default" /></template>
