<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q07pqcbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q07pqcbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-grid-line" /></template>
