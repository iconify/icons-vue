<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0x80go8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0x80go8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:drag-vertical" /></template>
