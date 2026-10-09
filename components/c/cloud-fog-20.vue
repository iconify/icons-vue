<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_ydbgbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o_ydbgbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-fog-20" /></template>
