<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjfh3_bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjfh3_bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:graph-pie" /></template>
