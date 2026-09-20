<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4krx_beo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4krx_beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-10-bluetooth" /></template>
