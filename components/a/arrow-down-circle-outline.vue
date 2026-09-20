<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9ql8lx2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9ql8lx2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-down-circle-outline" /></template>
