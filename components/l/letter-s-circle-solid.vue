<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2h-g4b0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2h-g4b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-s-circle-solid" /></template>
