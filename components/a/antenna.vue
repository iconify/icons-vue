<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsozpubbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsozpubbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:antenna" /></template>
