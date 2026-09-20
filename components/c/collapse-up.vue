<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv2nmoqxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qv2nmoqxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:collapse-up" /></template>
