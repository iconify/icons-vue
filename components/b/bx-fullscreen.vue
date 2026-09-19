<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtxw-s4kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtxw-s4kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-fullscreen" /></template>
