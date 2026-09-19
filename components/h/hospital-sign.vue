<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d96e75b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d96e75b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:hospital-sign" /></template>
