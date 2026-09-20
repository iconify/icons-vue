<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjd-vmbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjd-vmbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-negative" /></template>
