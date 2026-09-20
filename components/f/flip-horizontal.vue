<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qatnpcbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qatnpcbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:flip-horizontal" /></template>
