<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p13lpwbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p13lpwbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:info-box-outline" /></template>
