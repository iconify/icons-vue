<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vln3y5t7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vln3y5t7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-number-5-solid" /></template>
