<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qngb-pbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qngb-pbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hand-heart-line" /></template>
