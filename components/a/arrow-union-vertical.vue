<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsro9dbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsro9dbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-union-vertical" /></template>
