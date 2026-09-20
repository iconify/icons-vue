<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slffru9_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slffru9_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:axis-x-arrow" /></template>
