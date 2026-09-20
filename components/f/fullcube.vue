<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agzhzlb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="agzhzlb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:fullcube" /></template>
