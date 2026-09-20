<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rym_01uyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rym_01uyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-man-board" /></template>
