<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9gxq5xmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9gxq5xmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dashboard-fill" /></template>
