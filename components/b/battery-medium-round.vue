<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo8q_vbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo8q_vbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-medium-round" /></template>
