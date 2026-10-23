<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyo_xixvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyo_xixvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-off" /></template>
