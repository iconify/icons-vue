<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9_mr5btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9_mr5btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:egg-fill" /></template>
