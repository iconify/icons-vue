<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib4amlbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib4amlbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hat-2-fill" /></template>
