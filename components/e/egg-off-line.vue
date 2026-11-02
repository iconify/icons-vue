<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg4ad6btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg4ad6btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:egg-off-line" /></template>
