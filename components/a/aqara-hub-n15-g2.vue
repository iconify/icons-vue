<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojdde1gbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojdde1gbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-hub-n15-g2" /></template>
