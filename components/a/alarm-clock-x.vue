<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgf237vtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgf237vtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:alarm-clock-x" /></template>
