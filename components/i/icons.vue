<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgw446bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wgw446bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:icons" /></template>
