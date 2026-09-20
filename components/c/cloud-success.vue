<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq3x6t7op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="sq3x6t7op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-success" /></template>
