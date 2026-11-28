<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igx07ub6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igx07ub6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:align-center-solid" /></template>
