<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m05_qabul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m05_qabul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fast-arrow-left" /></template>
