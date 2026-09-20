<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfw00t5tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfw00t5tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:list-box-line" /></template>
