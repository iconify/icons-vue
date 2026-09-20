<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfk6fpb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfk6fpb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:group-detail-filled" /></template>
