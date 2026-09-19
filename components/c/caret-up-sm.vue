<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oppwr_pjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oppwr_pjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:caret-up-sm" /></template>
