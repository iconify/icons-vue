<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j62ekcbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j62ekcbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-square-rounded" /></template>
