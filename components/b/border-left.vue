<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8qnxxb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8qnxxb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:border-left" /></template>
