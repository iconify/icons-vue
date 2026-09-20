<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6eun1bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6eun1bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:forward" /></template>
