<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0oi0fhzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0oi0fhzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:drone" /></template>
