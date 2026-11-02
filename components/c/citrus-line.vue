<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tut8ix2_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tut8ix2_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:citrus-line" /></template>
