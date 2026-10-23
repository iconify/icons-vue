<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnlo_9ctj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnlo_9ctj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cigarette" /></template>
