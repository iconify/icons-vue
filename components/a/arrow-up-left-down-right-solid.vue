<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3cw-ybsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3cw-ybsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-up-left-down-right-solid" /></template>
