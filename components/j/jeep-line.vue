<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqp8m2bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqp8m2bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:jeep-line" /></template>
