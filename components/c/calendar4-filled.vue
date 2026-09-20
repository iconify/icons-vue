<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te1zobbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te1zobbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar4-filled" /></template>
