<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwp5anzju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwp5anzju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chevron-left" /></template>
