<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsm32d9mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xsm32d9mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:brilliance" /></template>
