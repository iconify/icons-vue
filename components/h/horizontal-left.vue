<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff-g0nb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff-g0nb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:horizontal-left" /></template>
