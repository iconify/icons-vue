<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbt-of79j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbt-of79j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:chart-network-solid" /></template>
