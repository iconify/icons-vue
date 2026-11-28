<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkdye4ghw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkdye4ghw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:lighthouse" /></template>
