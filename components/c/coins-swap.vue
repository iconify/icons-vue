<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztdm3ybgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztdm3ybgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:coins-swap" /></template>
