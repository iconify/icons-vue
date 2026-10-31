<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdicv_b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xdicv_b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-box-gabled-building-with-chimney" /></template>
