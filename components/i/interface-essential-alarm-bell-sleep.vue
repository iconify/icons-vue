<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvet70jfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rvet70jfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-alarm-bell-sleep" /></template>
