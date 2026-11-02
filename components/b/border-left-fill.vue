<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt1uengkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt1uengkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-left-fill" /></template>
