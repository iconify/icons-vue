<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj2dx1b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj2dx1b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lg-oled55" /></template>
