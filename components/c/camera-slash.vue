<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa1e3obbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa1e3obbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:camera-slash" /></template>
