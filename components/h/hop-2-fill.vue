<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv8zkgwyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv8zkgwyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hop-2-fill" /></template>
