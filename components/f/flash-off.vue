<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okd8awbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okd8awbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flash-off" /></template>
