<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl1q_wbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl1q_wbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-variant" /></template>
