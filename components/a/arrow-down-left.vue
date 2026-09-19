<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ack00vbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ack00vbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:arrow-down-left" /></template>
