<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6-qacbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6-qacbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-horizontal-justify-center-fill" /></template>
