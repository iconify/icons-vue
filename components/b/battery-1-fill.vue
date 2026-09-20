<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0fq-mbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0fq-mbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-1-fill" /></template>
