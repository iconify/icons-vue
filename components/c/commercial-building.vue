<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxpg19b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jxpg19b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:commercial-building" /></template>
