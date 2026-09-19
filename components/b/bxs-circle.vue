<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml94_-u6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml94_-u6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-circle" /></template>
