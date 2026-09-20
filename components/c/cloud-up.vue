<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzfl7tecj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="kzfl7tecj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:cloud-up" /></template>
