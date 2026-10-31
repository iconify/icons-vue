<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-ip83bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-ip83bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-help-round" /></template>
