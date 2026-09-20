<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/korua5bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="korua5bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-horizontal-justify-start" /></template>
