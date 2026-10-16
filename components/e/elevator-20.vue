<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyuwl4bpc.css';
import '../../css/m/m2qyafbre.css';
import '../../css/z/zi0m9n48q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vyuwl4bpc"/><path class="m2qyafbre"/><path class="zi0m9n48q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:elevator-20" /></template>
