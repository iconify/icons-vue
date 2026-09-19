<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdjsppbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdjsppbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:check" /></template>
