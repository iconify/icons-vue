<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2zk_9ikp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="m2zk_9ikp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:airplane-enabled-flat" /></template>
