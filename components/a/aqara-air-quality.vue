<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrh39abmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrh39abmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-air-quality" /></template>
