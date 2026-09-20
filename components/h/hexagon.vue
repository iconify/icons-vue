<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijp_u1bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijp_u1bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:hexagon" /></template>
