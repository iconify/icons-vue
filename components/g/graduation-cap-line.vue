<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqlr_ebwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqlr_ebwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:graduation-cap-line" /></template>
