<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v214gw1op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v214gw1op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-h1-3" /></template>
