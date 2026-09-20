<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbnx1ps0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbnx1ps0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:decimal-comma-increase" /></template>
