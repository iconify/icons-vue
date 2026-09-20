<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-ckjob3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-ckjob3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-robot-happy" /></template>
