<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs_00qnxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs_00qnxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-arrow-from-right" /></template>
