<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awn-39bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awn-39bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-arrow-to-left" /></template>
