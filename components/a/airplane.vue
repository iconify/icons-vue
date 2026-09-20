<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqp4kkbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqp4kkbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:airplane" /></template>
