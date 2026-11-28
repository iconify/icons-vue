<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um1e_otjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um1e_otjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:desktop-tower-lock" /></template>
