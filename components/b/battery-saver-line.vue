<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_u8-1key.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_u8-1key"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:battery-saver-line" /></template>
