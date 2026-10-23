<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv_m46rdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv_m46rdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:faucet" /></template>
