<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw-1_aciu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw-1_aciu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-7-fill" /></template>
