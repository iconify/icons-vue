<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikwr87_mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikwr87_mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-caret-down" /></template>
