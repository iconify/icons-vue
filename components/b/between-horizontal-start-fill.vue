<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1o11pevs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1o11pevs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:between-horizontal-start-fill" /></template>
