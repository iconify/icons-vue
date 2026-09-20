<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxy0f_iaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxy0f_iaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fountain-pen" /></template>
