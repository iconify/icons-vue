<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx8r--8tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx8r--8tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloudy-solid" /></template>
