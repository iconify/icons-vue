<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6yfbr_kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6yfbr_kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chart-b" /></template>
