<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikdh51bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ikdh51bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:face-scan-1" /></template>
