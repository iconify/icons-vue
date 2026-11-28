<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvz5j4bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvz5j4bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hdmi-port-solid" /></template>
