<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1w0_pbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="p1w0_pbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cube" /></template>
