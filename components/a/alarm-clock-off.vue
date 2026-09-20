<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuzqp_opo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuzqp_opo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:alarm-clock-off" /></template>
