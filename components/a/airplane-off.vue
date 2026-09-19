<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydz44ibch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydz44ibch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:airplane-off" /></template>
