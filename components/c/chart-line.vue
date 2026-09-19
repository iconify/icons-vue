<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_x46zk6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g_x46zk6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chart-line" /></template>
