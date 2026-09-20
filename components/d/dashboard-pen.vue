<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu7tyx5et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uu7tyx5et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:dashboard-pen" /></template>
