<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3v1wwjwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3v1wwjwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:line-chart" /></template>
