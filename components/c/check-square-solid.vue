<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzonygbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzonygbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:check-square-solid" /></template>
