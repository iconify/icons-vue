<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw_fxrxtk.css';
import '../../css/i/ivfjhjnom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw_fxrxtk"/><path class="ivfjhjnom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:desktop-mouse-2" /></template>
