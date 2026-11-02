<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw535xgbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw535xgbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-8-line" /></template>
