<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xno0b68zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xno0b68zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:construction" /></template>
