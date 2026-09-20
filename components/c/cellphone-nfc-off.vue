<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd191wbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd191wbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cellphone-nfc-off" /></template>
