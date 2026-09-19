<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7j2apbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7j2apbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-thermo-e1" /></template>
