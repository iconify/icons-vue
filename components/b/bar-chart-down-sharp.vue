<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2n4w53sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2n4w53sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-down-sharp" /></template>
