<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z51zl_eod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z51zl_eod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-dot-fill" /></template>
