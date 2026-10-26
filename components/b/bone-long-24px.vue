<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-yd735tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-yd735tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bone-long-24px" /></template>
