<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t39vyu_8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t39vyu_8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-h-diamond" /></template>
