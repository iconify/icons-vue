<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryo1eccnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryo1eccnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:close-circle-dash-line" /></template>
