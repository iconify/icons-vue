<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rla28bbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rla28bbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:cross-circle" /></template>
