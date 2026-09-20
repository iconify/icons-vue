<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfc2vbcbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfc2vbcbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:camcorder" /></template>
