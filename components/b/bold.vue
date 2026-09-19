<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0_dr5q8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0_dr5q8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:bold" /></template>
