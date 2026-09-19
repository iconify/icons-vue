<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf1w6ybal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qf1w6ybal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:home-modern-20-solid" /></template>
