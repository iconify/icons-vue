<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncmmujb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncmmujb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-left-solid" /></template>
