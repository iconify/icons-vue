<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfnabubzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfnabubzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:checkbook-arrow-left" /></template>
