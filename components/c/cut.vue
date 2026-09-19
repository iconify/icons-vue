<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhfjp-bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhfjp-bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cut" /></template>
