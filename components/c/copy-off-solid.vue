<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzmtn0xvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzmtn0xvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:copy-off-solid" /></template>
