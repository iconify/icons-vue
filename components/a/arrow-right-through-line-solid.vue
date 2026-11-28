<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djm0w-btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djm0w-btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-right-through-line-solid" /></template>
