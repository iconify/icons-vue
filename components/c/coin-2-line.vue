<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk-oenbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk-oenbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:coin-2-line" /></template>
