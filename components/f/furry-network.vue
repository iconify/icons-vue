<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg5a_1n1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg5a_1n1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:furry-network" /></template>
