<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w29elplbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w29elplbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:heart-line" /></template>
