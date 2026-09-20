<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys6vs2qzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys6vs2qzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-1-line" /></template>
