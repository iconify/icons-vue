<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj_hqcc3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj_hqcc3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-plus" /></template>
