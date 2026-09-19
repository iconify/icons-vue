<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt9eulz_o.css';
import '../../css/o/o0m5y054f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt9eulz_o"/><path class="o0m5y054f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:donut" /></template>
