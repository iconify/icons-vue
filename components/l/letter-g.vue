<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykq264b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykq264b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-g" /></template>
