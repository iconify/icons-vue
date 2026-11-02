<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sughtb71e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sughtb71e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:capricorn-fill" /></template>
