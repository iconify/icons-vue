<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2xw8u1ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2xw8u1ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-warning-line" /></template>
