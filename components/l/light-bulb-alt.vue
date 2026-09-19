<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4agvvbwr.css';
import '../../css/v/vy6hizqps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4agvvbwr"/><path class="vy6hizqps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:light-bulb-alt" /></template>
