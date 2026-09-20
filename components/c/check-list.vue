<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p770-7bjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p770-7bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:check-list" /></template>
