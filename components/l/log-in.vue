<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufujoebnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufujoebnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:log-in" /></template>
