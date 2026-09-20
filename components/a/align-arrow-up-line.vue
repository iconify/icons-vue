<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dly37_bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dly37_bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-arrow-up-line" /></template>
