<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iovcf-yyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iovcf-yyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:gamepad-plus" /></template>
