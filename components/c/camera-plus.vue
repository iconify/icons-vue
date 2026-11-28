<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8-lfq-sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8-lfq-sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:camera-plus" /></template>
