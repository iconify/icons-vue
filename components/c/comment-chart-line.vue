<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp3w_wbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp3w_wbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-chart-line" /></template>
