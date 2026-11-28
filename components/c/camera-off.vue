<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwjuxs-hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwjuxs-hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:camera-off" /></template>
