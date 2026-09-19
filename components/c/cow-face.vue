<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsabh2boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xsabh2boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cow-face" /></template>
