<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov19mnblx.css';
import '../../css/z/zpo4y_beo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ov19mnblx"/><path class="zpo4y_beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-20-bold" /></template>
