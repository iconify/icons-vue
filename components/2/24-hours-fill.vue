<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qch9_uvyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qch9_uvyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:24-hours-fill" /></template>
