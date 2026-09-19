<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_q5-s7-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_q5-s7-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-refresh" /></template>
