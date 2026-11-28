<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy9yfibzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy9yfibzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-x-solid" /></template>
