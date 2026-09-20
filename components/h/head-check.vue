<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir3np9cpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir3np9cpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-check" /></template>
