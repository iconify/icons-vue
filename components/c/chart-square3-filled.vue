<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri9akzb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri9akzb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chart-square3-filled" /></template>
