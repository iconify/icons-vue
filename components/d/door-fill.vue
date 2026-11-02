<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd7_f5brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd7_f5brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:door-fill" /></template>
