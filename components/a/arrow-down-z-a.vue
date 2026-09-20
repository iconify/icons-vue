<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggzg1wb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggzg1wb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-z-a" /></template>
