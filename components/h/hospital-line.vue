<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plc_te-wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plc_te-wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hospital-line" /></template>
