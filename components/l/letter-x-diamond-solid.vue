<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz1-jibwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz1-jibwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-x-diamond-solid" /></template>
