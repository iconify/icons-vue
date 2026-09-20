<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd2r_sbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd2r_sbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:guitar" /></template>
