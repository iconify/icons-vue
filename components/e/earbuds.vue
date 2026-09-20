<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynurgz41l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynurgz41l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:earbuds" /></template>
