<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrf_klbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrf_klbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:cooker-extract-off" /></template>
