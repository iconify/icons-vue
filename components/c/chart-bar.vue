<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4f2kpbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4f2kpbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chart-bar" /></template>
