<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivbhlbb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ivbhlbb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:ballot-box-with-check" /></template>
