<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxng7opnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxng7opnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:living-room" /></template>
