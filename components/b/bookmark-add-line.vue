<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-wrg7omj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-wrg7omj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-add-line" /></template>
