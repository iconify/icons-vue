<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5naakbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a5naakbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-wind-48" /></template>
