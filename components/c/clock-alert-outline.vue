<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1o_rnbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1o_rnbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-alert-outline" /></template>
