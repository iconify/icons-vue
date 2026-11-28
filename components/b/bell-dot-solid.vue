<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4md1owgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4md1owgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bell-dot-solid" /></template>
