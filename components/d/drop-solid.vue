<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou-24ml_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou-24ml_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:drop-solid" /></template>
