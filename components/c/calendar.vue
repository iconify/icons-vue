<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kam2ibkwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kam2ibkwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:calendar" /></template>
