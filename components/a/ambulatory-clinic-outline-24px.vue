<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf2_240wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tf2_240wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ambulatory-clinic-outline-24px" /></template>
