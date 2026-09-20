<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqgn-lbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqgn-lbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-w-square-solid" /></template>
