<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc54xowtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc54xowtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:basketball-fill" /></template>
