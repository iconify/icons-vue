<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2206v69j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2206v69j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-up-box-line" /></template>
