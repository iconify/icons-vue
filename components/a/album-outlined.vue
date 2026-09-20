<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub3lhrgwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub3lhrgwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:album-outlined" /></template>
