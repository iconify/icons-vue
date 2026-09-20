<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ket8acckj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ket8acckj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:filter" /></template>
