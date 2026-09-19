<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icmq1lb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icmq1lb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:currency-lira" /></template>
