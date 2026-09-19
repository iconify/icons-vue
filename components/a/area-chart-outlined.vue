<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-2451v-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q-2451v-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:area-chart-outlined" /></template>
