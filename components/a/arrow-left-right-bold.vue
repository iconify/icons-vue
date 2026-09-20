<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhs2ozbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhs2ozbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-right-bold" /></template>
