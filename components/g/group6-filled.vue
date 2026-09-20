<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbw2iscqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbw2iscqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:group6-filled" /></template>
