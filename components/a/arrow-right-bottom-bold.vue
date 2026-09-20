<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi64abo0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi64abo0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-right-bottom-bold" /></template>
