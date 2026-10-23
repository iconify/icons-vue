<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7s9p8byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7s9p8byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:line-dot-left-horizontal" /></template>
