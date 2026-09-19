<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l45hi9gsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="l45hi9gsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:cloud-refresh" /></template>
