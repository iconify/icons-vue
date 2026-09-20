<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyw1evzrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyw1evzrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:kitchen-roll" /></template>
