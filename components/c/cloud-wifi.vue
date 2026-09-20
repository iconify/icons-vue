<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwbuhqa_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zwbuhqa_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-wifi" /></template>
