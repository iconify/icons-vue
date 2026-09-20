<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tay96syqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tay96syqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:airport-plane" /></template>
