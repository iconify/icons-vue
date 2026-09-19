<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0htpwbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q0htpwbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-90deg-up" /></template>
