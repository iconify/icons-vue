<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9udfcbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9udfcbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-vertical-justify-end" /></template>
