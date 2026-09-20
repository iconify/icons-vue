<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khj3moalm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="khj3moalm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:budget-board-light" /></template>
