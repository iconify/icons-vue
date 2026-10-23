<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqec03jgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqec03jgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gap-horizontal" /></template>
