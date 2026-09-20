<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yby7n0bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yby7n0bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-left-up" /></template>
