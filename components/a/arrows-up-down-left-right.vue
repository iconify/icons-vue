<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8ba5lbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l8ba5lbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrows-up-down-left-right" /></template>
