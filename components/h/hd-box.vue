<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd_g14sid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd_g14sid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hd-box" /></template>
