<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3ojxbk_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3ojxbk_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-left-down-arrow-circle" /></template>
