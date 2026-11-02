<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4kt-3w1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4kt-3w1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:check-circle-dash-line" /></template>
