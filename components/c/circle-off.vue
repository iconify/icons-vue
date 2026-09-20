<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvdrhhj_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvdrhhj_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-off" /></template>
