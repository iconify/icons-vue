<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_gtx87xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_gtx87xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:empty-box-line" /></template>
