<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3ieeccwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3ieeccwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:align-horizontal-space-between" /></template>
