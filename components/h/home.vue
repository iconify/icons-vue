<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2ky_fbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2ky_fbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home" /></template>
