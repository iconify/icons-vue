<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcbn25zhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="xcbn25zhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:desktop" /></template>
