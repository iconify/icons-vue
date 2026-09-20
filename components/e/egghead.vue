<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxzkd_ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxzkd_ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:egghead" /></template>
