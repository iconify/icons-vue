<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkdayxurj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkdayxurj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:battery-bolt" /></template>
