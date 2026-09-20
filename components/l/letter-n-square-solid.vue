<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yptlkpd2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yptlkpd2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-n-square-solid" /></template>
