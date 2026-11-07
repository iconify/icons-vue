<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w04165mul.css';
import '../../css/o/on5h-v5us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w04165mul"/><path class="on5h-v5us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:import-outline" /></template>
