<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aihnf6bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aihnf6bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-decrease-line" /></template>
