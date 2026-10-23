<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r36lvjb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r36lvjb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gap-vertical" /></template>
