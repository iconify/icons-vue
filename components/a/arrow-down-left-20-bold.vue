<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az1dy05bx.css';
import '../../css/x/xh-xqdv8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="az1dy05bx"/><path class="xh-xqdv8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-down-left-20-bold" /></template>
