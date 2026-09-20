<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azme87jwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azme87jwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-variant-plus-outline" /></template>
