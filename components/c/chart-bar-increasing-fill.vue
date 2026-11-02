<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc3b0korc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc3b0korc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-bar-increasing-fill" /></template>
