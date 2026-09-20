<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq3zmtb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hq3zmtb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:disk-pen" /></template>
