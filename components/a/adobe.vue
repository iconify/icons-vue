<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbrqyjb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="mbrqyjb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:adobe" /></template>
