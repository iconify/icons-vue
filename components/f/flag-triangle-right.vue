<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acwpuejmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acwpuejmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:flag-triangle-right" /></template>
