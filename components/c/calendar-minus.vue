<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp6js4-lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp6js4-lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:calendar-minus" /></template>
