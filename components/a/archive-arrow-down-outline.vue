<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrn74jbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrn74jbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive-arrow-down-outline" /></template>
