<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqz1thb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cqz1thb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:donut" /></template>
