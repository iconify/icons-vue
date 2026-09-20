<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeo0tq68l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qeo0tq68l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:cactus" /></template>
