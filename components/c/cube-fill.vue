<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml1xv_bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml1xv_bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cube-fill" /></template>
