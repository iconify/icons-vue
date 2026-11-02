<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1_53rbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1_53rbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dividing-line-line" /></template>
