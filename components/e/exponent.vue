<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbi8albbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbi8albbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:exponent" /></template>
