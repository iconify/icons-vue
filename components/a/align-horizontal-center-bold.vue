<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv5slx5dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv5slx5dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-horizontal-center-bold" /></template>
