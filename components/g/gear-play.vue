<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coebxcb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coebxcb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gear-play" /></template>
