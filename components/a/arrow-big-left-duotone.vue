<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk43z12xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary xk43z12xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-big-left-duotone" /></template>
